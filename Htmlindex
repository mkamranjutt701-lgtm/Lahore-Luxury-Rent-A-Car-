export default function LahoreLuxuryRentACar() { const cars = [ { name: 'Jetour X70 Plus', price: '15,000 PKR / Day', image: 'https://images.unsplash.com/photo-1503376780353-7e6692767b70?q=80&w=1400&auto=format&fit=crop', }, { name: 'Toyota Prado', price: '25,000 PKR / Day', image: 'https://images.unsplash.com/photo-1494976388531-d1058494cdd8?q=80&w=1400&auto=format&fit=crop', }, { name: 'Honda Civic', price: '12,000 PKR / Day', image: 'https://images.unsplash.com/photo-1552519507-da3b142c6e3d?q=80&w=1400&auto=format&fit=crop', }, ];

return ( <div className="bg-black text-white min-h-screen font-sans"> <header className="fixed top-0 left-0 w-full z-50 backdrop-blur-md bg-black/40 border-b border-yellow-500/20"> <div className="max-w-7xl mx-auto flex items-center justify-between px-6 py-4"> <div> <h1 className="text-2xl font-bold text-yellow-400"> Lahore Luxury Rent A Car </h1> </div>

<a
        href="https://wa.me/923104569041"
        className="bg-yellow-500 text-black px-5 py-2 rounded-full font-semibold hover:scale-105 transition"
      >
        WhatsApp Booking
      </a>
    </div>
  </header>

  <section
    className="h-screen bg-cover bg-center flex items-center justify-center text-center relative"
    style={{
      backgroundImage:
        "url('https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?q=80&w=1600&auto=format&fit=crop')",
    }}
  >
    <div className="absolute inset-0 bg-black/70"></div>

    <div className="relative z-10 px-6">
      <p className="uppercase tracking-[8px] text-yellow-400 mb-4">
        Premium Luxury Cars
      </p>

      <h2 className="text-5xl md:text-7xl font-extrabold leading-tight mb-6">
        Drive Lahore <br /> In Style
      </h2>

      <p className="text-gray-300 max-w-2xl mx-auto mb-8 text-lg">
        Experience premium luxury car rentals in Lahore with professional
        service, stylish vehicles, and 24/7 booking support.
      </p>

      <div className="flex gap-4 justify-center flex-wrap">
        <a
          href="#cars"
          className="bg-yellow-500 text-black px-8 py-3 rounded-full font-bold hover:scale-105 transition"
        >
          Explore Cars
        </a>

        <a
          href="https://wa.me/923104569041"
          className="border border-yellow-500 text-yellow-400 px-8 py-3 rounded-full font-bold hover:bg-yellow-500 hover:text-black transition"
        >
          Book Now
        </a>
      </div>
    </div>
  </section>

  <section id="cars" className="max-w-7xl mx-auto px-6 py-24">
    <div className="text-center mb-16">
      <p className="text-yellow-400 uppercase tracking-[6px] mb-3">
        Our Fleet
      </p>
      <h3 className="text-4xl md:text-5xl font-bold">
        Premium Cars Collection
      </h3>
    </div>

    <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
      {cars.map((car, index) => (
        <div
          key={index}
          className="bg-white/5 backdrop-blur-md rounded-3xl overflow-hidden border border-white/10 hover:border-yellow-500/50 transition duration-300 hover:-translate-y-2"
        >
          <img
            src={car.image}
            alt={car.name}
            className="h-64 w-full object-cover"
          />

          <div className="p-6">
            <h4 className="text-2xl font-bold mb-2">{car.name}</h4>

            <p className="text-yellow-400 text-lg mb-5">{car.price}</p>

            <a
              href="https://wa.me/923104569041"
              className="block text-center bg-yellow-500 text-black py-3 rounded-full font-bold hover:scale-105 transition"
            >
              Book on WhatsApp
            </a>
          </div>
        </div>
      ))}
    </div>
  </section>

  <section className="bg-gradient-to-r from-yellow-500/10 to-black py-24 px-6">
    <div className="max-w-6xl mx-auto grid md:grid-cols-2 gap-10 items-center">
      <div>
        <p className="uppercase tracking-[5px] text-yellow-400 mb-4">
          Why Choose Us
        </p>

        <h3 className="text-5xl font-bold mb-6 leading-tight">
          Luxury Experience <br /> With Trusted Service
        </h3>

        <p className="text-gray-300 text-lg leading-relaxed">
          We provide premium luxury vehicles in Lahore with professional
          drivers, affordable pricing, and fast WhatsApp booking service.
        </p>
      </div>

      <div className="grid grid-cols-2 gap-5">
        {[
          '24/7 Service',
          'Luxury Cars',
          'Professional Drivers',
          'Affordable Rates',
        ].map((item, index) => (
          <div
            key={index}
            className="bg-white/5 border border-white/10 rounded-3xl p-8 text-center hover:border-yellow-500/50 transition"
          >
            <h4 className="text-xl font-bold">{item}</h4>
          </div>
        ))}
      </div>
    </div>
  </section>

  <footer className="py-10 border-t border-white/10 text-center px-6">
    <h4 className="text-3xl font-bold text-yellow-400 mb-3">
      Lahore Luxury Rent A Car
    </h4>

    <p className="text-gray-400 mb-4">
      WhatsApp & Call: 0310 4569041
    </p>

    <a
      href="https://wa.me/923104569041"
      className="inline-block bg-yellow-500 text-black px-8 py-3 rounded-full font-bold hover:scale-105 transition"
    >
      Contact on WhatsApp
    </a>
  </footer>
</div>

); }
