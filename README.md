# Birthday-website
Romantic birthday website
export default function RomanticBirthdayWebsite() { return ( <div className="min-h-screen bg-gradient-to-b from-pink-100 via-rose-50 to-white text-gray-800"> {/* Hero Section */} <section className="min-h-screen flex flex-col items-center justify-center text-center px-6"> <div className="max-w-3xl"> <h1 className="text-5xl md:text-7xl font-bold text-rose-600 mb-6"> Happy Birthday, My Love ❤️ </h1> <p className="text-xl md:text-2xl leading-relaxed mb-8"> Every moment with you is a beautiful memory. Today, I celebrate the most special person in my life. </p> <div className="text-6xl animate-bounce">🎂💖🎉</div> </div> </section>

{/* Love Message */}
  <section className="py-20 px-6">
    <div className="max-w-4xl mx-auto bg-white/80 backdrop-blur rounded-3xl shadow-xl p-10 md:p-16">
      <h2 className="text-4xl font-bold text-center text-rose-500 mb-8">
        A Letter for You 💌
      </h2>
      <p className="text-lg md:text-xl leading-9 text-center">
        You are the reason behind my smiles, my happiness, and my favorite
        memories. Your kindness, your laughter, and your love make every day
        brighter. On your birthday, I want you to know how deeply you are
        loved and how grateful I am to have you in my life.
        <br />
        <br />
        May your heart always be filled with joy, your dreams come true, and
        your beautiful smile never fade.
        <br />
        <br />
        <span className="font-semibold text-rose-600">
          I love you more than words can ever express. ❤️
        </span>
      </p>
    </div>
  </section>

  {/* Memories */}
  <section className="py-20 px-6 bg-rose-50">
    <div className="max-w-6xl mx-auto">
      <h2 className="text-4xl font-bold text-center text-rose-500 mb-12">
        Our Beautiful Memories 📸
      </h2>
      <div className="grid md:grid-cols-3 gap-8">
        {[
          'https://images.unsplash.com/photo-1516589178581-6cd7833ae3b2?auto=format&fit=crop&w=800&q=80',
          'https://images.unsplash.com/photo-1524504388940-b1c1722653e1?auto=format&fit=crop&w=800&q=80',
          'https://images.unsplash.com/photo-1517841905240-472988babdf9?auto=format&fit=crop&w=800&q=80',
        ].map((src, index) => (
          <img
            key={index}
            src={src}
            alt={`Memory ${index + 1}`}
            className="w-full h-80 object-cover rounded-3xl shadow-lg hover:scale-105 transition-transform duration-300"
          />
        ))}
      </div>
      <p className="text-center mt-6 text-gray-600">
        Replace these photos with your own favorite memories together.
      </p>
    </div>
  </section>

  {/* Reasons I Love You */}
  <section className="py-20 px-6">
    <div className="max-w-5xl mx-auto">
      <h2 className="text-4xl font-bold text-center text-rose-500 mb-12">
        Reasons I Love You 🌹
      </h2>
      <div className="grid md:grid-cols-2 gap-6">
        {[
          'Your beautiful smile',
          'Your caring heart',
          'The way you understand me',
          'Your endless support',
          'Your laughter',
          'The happiness you bring',
        ].map((reason, i) => (
          <div
            key={i}
            className="bg-white rounded-2xl shadow-md p-6 text-lg font-medium"
          >
            ❤️ {reason}
          </div>
        ))}
      </div>
    </div>
  </section>

  {/* Final Surprise */}
  <section className="py-24 px-6 bg-gradient-to-r from-rose-500 to-pink-500 text-white text-center">
    <h2 className="text-5xl font-bold mb-6">Forever & Always 💍</h2>
    <p className="text-xl max-w-3xl mx-auto leading-8">
      No matter where life takes us, my heart will always belong to you.
      Thank you for being my love, my best friend, and my greatest blessing.
    </p>
    <p className="mt-10 text-3xl font-semibold">Happy Birthday, My Love! ❤️🎂</p>
  </section>
</div>

); }
