{/* CONTACT */}
<section id="contact" className="py-20 max-w-5xl mx-auto px-4">
  <h2 className="text-3xl font-bold mb-6">Contact & Social Media</h2>

  <div className="grid md:grid-cols-2 gap-6">

    {/* CONTACT BUTTONS */}
    <div className="space-y-4">
      <a href="https://wa.me/252615614785" className="flex items-center gap-2 p-4 bg-green-500 rounded-xl hover:scale-105 transition">
        <MessageCircle/> WhatsApp
      </a>

      <a href="tel:+252615614785" className="flex items-center gap-2 p-4 bg-blue-500 rounded-xl hover:scale-105 transition">
        <Phone/> Call
      </a>

      <a href="mailto:macalimmaxamadnuurkuuloow@gmail.com" className="flex items-center gap-2 p-4 bg-purple-500 rounded-xl hover:scale-105 transition">
        <Mail/> Email
      </a>
    </div>

    {/* SOCIAL MEDIA */}
    <div className="space-y-4">

      {/* FACEBOOK */}
      <a
        href="https://facebook.com/macalimmaxamadnuur"
        target="_blank"
        rel="noreferrer"
        className="flex items-center gap-2 p-4 bg-blue-600 rounded-xl hover:scale-105 transition"
      >
        <Facebook/> Facebook
      </a>

      {/* TELEGRAM */}
      <a
        href="https://t.me/Macalimmaxamadnuur"
        target="_blank"
        rel="noreferrer"
        className="flex items-center gap-2 p-4 bg-sky-500 rounded-xl hover:scale-105 transition"
      >
        <Send/> Telegram
      </a>

      {/* 🔥 LINKTREE ADDED */}
      <a
        href="https://linktr.ee/Macalimaxamadnuur"
        target="_blank"
        rel="noreferrer"
        className="flex items-center gap-2 p-4 bg-gradient-to-r from-purple-600 to-pink-500 rounded-xl hover:scale-105 transition font-semibold"
      >
        🌐 Linktree - All My Links
      </a>

      {/* WHATSAPP CHANNEL */}
      <a
        href="https://wa.me/252615614785"
        className="flex items-center gap-2 p-4 bg-green-500 rounded-xl hover:scale-105 transition"
      >
        <MessageCircle/> WhatsApp Channel
      </a>

    </div>

  </div>

  {/* FORM */}
  <form className="mt-8 space-y-3">
    <input className="w-full p-3 bg-white/5 rounded-lg" placeholder="Your Name" />
    <input className="w-full p-3 bg-white/5 rounded-lg" placeholder="Your Email" />
    <textarea className="w-full p-3 bg-white/5 rounded-lg" placeholder="Message" />
    <button className="w-full p-3 bg-blue-500 rounded-lg hover:bg-blue-600 transition">
      Send Message
    </button>
  </form>
</section>
