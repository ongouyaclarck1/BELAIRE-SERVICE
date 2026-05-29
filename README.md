export default function BelaireServiceWebsite() {
  const services = [
    {
      title: 'Dépannage & Maintenance PC',
      price: 'À partir de 4 000 FCFA',
      description:
        'Réparation ordinateurs lents ou bloqués, nettoyage virus et optimisation.',
      icon: '🛠️',
    },
    {
      title: 'Installation Windows & Logiciels',
      price: 'À partir de 8 000 FCFA',
      description:
        'Installation Windows 10/11 et tous types de logiciels.',
      icon: '💻',
    },
    {
      title: 'Réseaux & Connexions',
      price: 'À partir de 2 500 FCFA',
      description:
        'Configuration Wi‑Fi, routeur, réseau local et partage sécurisé.',
      icon: '📶',
    },
    {
      title: 'Cybersécurité',
      price: 'À partir de 5 000 FCFA',
      description:
        'Protection contre virus, piratage et sécurisation des appareils.',
      icon: '🔒',
    },
    {
      title: 'Création de Sites Web',
      price: 'À partir de 50 000 FCFA',
      description:
        'Sites vitrines professionnels modernes et présence en ligne.',
      icon: '🌐',
    },
    {
      title: 'Formations Informatiques',
      price: 'À partir de 5 000 FCFA',
      description:
        'Formation Windows, Word, Excel, Internet et sécurité informatique.',
      icon: '🎓',
    },
  ]

  return (
    <main className="min-h-screen bg-black text-white overflow-hidden">
      {/* NAVBAR */}
      <nav className="fixed top-0 w-full z-50 bg-black/80 backdrop-blur-xl border-b border-blue-950">
        <div className="max-w-7xl mx-auto flex items-center justify-between px-6 py-5">
          <div>
            <h1 className="text-3xl font-black tracking-tight">
              BELAIRE <span className="text-blue-500">SERVICE</span>
            </h1>
          </div>

          <div className="hidden md:flex gap-8 text-gray-300 font-medium">
            <a href="#home" className="hover:text-blue-400 transition">Accueil</a>
            <a href="#services" className="hover:text-blue-400 transition">Services</a>
            <a href="#about" className="hover:text-blue-400 transition">À propos</a>
            <a href="#contact" className="hover:text-blue-400 transition">Contact</a>
          </div>

          <a
            href="https://wa.me/242066365142"
            className="bg-blue-600 hover:bg-blue-500 transition px-5 py-3 rounded-2xl font-semibold shadow-lg shadow-blue-600/30"
          >
            WhatsApp
          </a>
        </div>
      </nav>

      {/* HERO */}
      <section
        id="home"
        className="relative min-h-screen flex items-center justify-center px-6 pt-32"
      >
        <div className="absolute inset-0 bg-gradient-to-b from-blue-900/20 to-black"></div>

        <div className="absolute top-40 left-10 w-72 h-72 bg-blue-500/20 rounded-full blur-3xl"></div>
        <div className="absolute bottom-20 right-10 w-72 h-72 bg-blue-700/20 rounded-full blur-3xl"></div>

        <div className="relative z-10 max-w-7xl grid lg:grid-cols-2 gap-20 items-center">
          <div>
            <p className="text-blue-400 uppercase tracking-[0.3em] font-semibold mb-5">
              Informatique • Maintenance • Web
            </p>

            <h1 className="text-6xl md:text-8xl font-black leading-none mb-8">
              BELAIRE
              <span className="block text-blue-500">SERVICES</span>
            </h1>

            <p className="text-xl text-gray-300 leading-9 max-w-2xl mb-10">
              Votre solution informatique rapide, fiable et professionnelle.
              Nous vous accompagnons dans la maintenance, la cybersécurité,
              les réseaux, la création de sites web et les formations.
            </p>

            <div className="flex flex-wrap gap-5">
              <a
                href="https://wa.me/242066365142"
                className="bg-blue-600 hover:bg-blue-500 transition px-8 py-4 rounded-2xl text-lg font-bold shadow-xl shadow-blue-600/30"
              >
                Contacter sur WhatsApp
              </a>

              <a
                href="#services"
                className="border border-blue-800 hover:bg-blue-950 transition px-8 py-4 rounded-2xl text-lg font-semibold"
              >
                Voir les services
              </a>
            </div>

            <div className="grid md:grid-cols-3 gap-5 mt-14">
              <div className="bg-zinc-950 border border-blue-950 rounded-3xl p-5">
                <h3 className="text-3xl font-black text-blue-500">24/7</h3>
                <p className="text-gray-400 mt-2">Support rapide</p>
              </div>

              <div className="bg-zinc-950 border border-blue-950 rounded-3xl p-5">
                <h3 className="text-3xl font-black text-blue-500">100%</h3>
                <p className="text-gray-400 mt-2">Fiable & sécurisé</p>
              </div>

              <div className="bg-zinc-950 border border-blue-950 rounded-3xl p-5">
                <h3 className="text-3xl font-black text-blue-500">Pro</h3>
                <p className="text-gray-400 mt-2">Solutions modernes</p>
              </div>
            </div>
          </div>

          <div className="relative">
            <div className="bg-gradient-to-br from-blue-600 to-blue-900 p-[1px] rounded-[40px] shadow-2xl shadow-blue-700/20">
              <div className="bg-black rounded-[40px] p-10 border border-blue-950">
                <img
                  src="https://images.unsplash.com/photo-1518770660439-4636190af475?q=80&w=1200&auto=format&fit=crop"
                  alt="ordinateur"
                  className="rounded-3xl object-cover w-full h-[500px]"
                />
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* SERVICES */}
      <section id="services" className="max-w-7xl mx-auto px-6 py-28">
        <div className="text-center mb-20">
          <p className="text-blue-400 uppercase tracking-[0.3em] font-semibold mb-5">
            Nos Services
          </p>

          <h2 className="text-5xl md:text-6xl font-black mb-6">
            Des solutions adaptées
          </h2>

          <p className="text-gray-400 text-xl max-w-3xl mx-auto leading-8">
            Nous proposons des services informatiques professionnels pour
            particuliers, étudiants, entreprises et créateurs.
          </p>
        </div>

        <div className="grid md:grid-cols-2 xl:grid-cols-3 gap-8">
          {services.map((service, index) => (
            <div
              key={index}
              className="bg-zinc-950 border border-blue-950 rounded-[32px] p-8 hover:-translate-y-2 hover:border-blue-700 transition duration-300"
            >
              <div className="text-6xl mb-6">{service.icon}</div>

              <h3 className="text-3xl font-bold mb-4 text-blue-400">
                {service.title}
              </h3>

              <p className="text-gray-400 leading-8 mb-8 text-lg">
                {service.description}
              </p>

              <div className="flex items-center justify-between">
                <span className="text-white font-black text-2xl">
                  {service.price}
                </span>

                <a
                  href="https://wa.me/242066365142"
                  className="bg-blue-600 hover:bg-blue-500 transition px-5 py-3 rounded-xl font-semibold"
                >
                  Réserver
                </a>
              </div>
            </div>
          ))}
        </div>
      </section>

      {/* ABOUT */}
      <section id="about" className="py-28 px-6 bg-zinc-950 border-y border-blue-950">
        <div className="max-w-6xl mx-auto grid lg:grid-cols-2 gap-16 items-center">
          <div>
            <p className="text-blue-400 uppercase tracking-[0.3em] font-semibold mb-5">
              Pourquoi nous ?
            </p>

            <h2 className="text-5xl font-black leading-tight mb-8">
              Une assistance informatique moderne et fiable.
            </h2>

            <p className="text-gray-400 text-xl leading-9 mb-10">
              Belaire Service accompagne ses clients avec des solutions rapides,
              professionnelles et sécurisées. Nous intervenons sur la maintenance
              PC, les réseaux, la cybersécurité et la création de solutions web.
            </p>

            <div className="space-y-5">
              <div className="flex items-center gap-4">
                <div className="w-4 h-4 rounded-full bg-blue-500"></div>
                <p className="text-lg text-gray-300">Intervention rapide</p>
              </div>

              <div className="flex items-center gap-4">
                <div className="w-4 h-4 rounded-full bg-blue-500"></div>
                <p className="text-lg text-gray-300">Support professionnel</p>
              </div>

              <div className="flex items-center gap-4">
                <div className="w-4 h-4 rounded-full bg-blue-500"></div>
                <p className="text-lg text-gray-300">Sécurité & optimisation</p>
              </div>
            </div>
          </div>

          <div className="bg-black border border-blue-950 rounded-[40px] p-10 shadow-2xl shadow-blue-900/20">
            <div className="grid grid-cols-2 gap-6">
              <div className="bg-zinc-950 rounded-3xl p-8 border border-blue-950">
                <h3 className="text-5xl font-black text-blue-500">6+</h3>
                <p className="text-gray-400 mt-3">Services professionnels</p>
              </div>

              <div className="bg-zinc-950 rounded-3xl p-8 border border-blue-950">
                <h3 className="text-5xl font-black text-blue-500">24h</h3>
                <p className="text-gray-400 mt-3">Réponse rapide</p>
              </div>

              <div className="bg-zinc-950 rounded-3xl p-8 border border-blue-950">
                <h3 className="text-5xl font-black text-blue-500">100%</h3>
                <p className="text-gray-400 mt-3">Support personnalisé</p>
              </div>

              <div className="bg-zinc-950 rounded-3xl p-8 border border-blue-950">
                <h3 className="text-5xl font-black text-blue-500">Pro</h3>
                <p className="text-gray-400 mt-3">Solutions fiables</p>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* CONTACT */}
      <section id="contact" className="max-w-7xl mx-auto px-6 py-28">
        <div className="bg-gradient-to-br from-blue-950 to-black border border-blue-900 rounded-[40px] p-12">
          <div className="grid lg:grid-cols-2 gap-16 items-center">
            <div>
              <p className="text-blue-400 uppercase tracking-[0.3em] font-semibold mb-5">
                Contact
              </p>

              <h2 className="text-5xl font-black mb-8">
                Disponible pour tous vos besoins informatiques.
              </h2>

              <p className="text-xl text-gray-300 leading-9">
                Contactez-nous dès maintenant pour une assistance rapide et
                professionnelle.
              </p>
            </div>

            <div className="space-y-6">
              <div className="bg-black/50 border border-blue-950 rounded-3xl p-8">
                <p className="text-gray-400 mb-3">WhatsApp</p>
                <h3 className="text-4xl font-black text-blue-400">
                  +242 06 636 51 42
                </h3>
              </div>

              <div className="bg-black/50 border border-blue-950 rounded-3xl p-8">
                <p className="text-gray-400 mb-3">Email</p>
                <h3 className="text-2xl font-bold break-all">
                  ongouyaclarck1@gmail.com
                </h3>
              </div>

              <a
                href="https://wa.me/242066365142"
                className="block w-full text-center bg-blue-600 hover:bg-blue-500 transition px-8 py-5 rounded-2xl text-xl font-bold shadow-xl shadow-blue-600/30"
              >
                Envoyer un message WhatsApp
              </a>
            </div>
          </div>
        </div>
      </section>

      {/* FOOTER */}
      <footer className="border-t border-blue-950 py-10 px-6">
        <div className="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-6">
          <div>
            <h2 className="text-3xl font-black">
              BELAIRE <span className="text-blue-500">SERVICE</span>
            </h2>

            <p className="text-gray-500 mt-3">
              Votre solution informatique rapide, fiable et professionnelle.
            </p>
          </div>

          <p className="text-gray-500 text-center md:text-right">
            © 2026 Belaire Service — Tous droits réservés.
          </p>
        </div>
      </footer>
    </main>
  )
}
