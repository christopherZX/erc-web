# erc-webconst Hero = () => {
  return (
    <section className="relative h-screen text-white">
      
      {/* Imagen de fondo */}
      <img
        src="/images/hero.jpg"
        className="absolute w-full h-full object-cover"
      />

      {/* Overlay oscuro */}
      <div className="absolute w-full h-full bg-black/60"></div>

      {/* Contenido */}
      <div className="relative z-10 max-w-6xl mx-auto px-6 h-full flex flex-col justify-center">
        
        <span className="bg-orange-500 text-sm px-4 py-1 rounded-full w-max mb-4">
          MAESTRO CONSTRUCTOR CERTIFICADO
        </span>

        <h1 className="text-5xl md:text-7xl font-bold leading-tight">
          Eric Ricardo <br />
          <span className="text-orange-400">Carrasco</span>
        </h1>

        <p className="mt-4 max-w-xl text-gray-200">
          Soluciones integrales en construcción, gasfitería e instalaciones.
        </p>

        {/* Botones */}
        <div className="mt-6 flex gap-4">
          <button className="bg-orange-500 px-6 py-3 rounded-full">
            Ver Servicios
          </button>

          <a
            href="tel:+56962991285"
            className="border border-white px-6 py-3 rounded-full"
          >
            Llamar Ahora
          </a>
        </div>

      </div>

      {/* Stats */}
      <div className="absolute bottom-0 w-full bg-black/80 py-6 flex justify-around text-center">
        <div>
          <h2 className="text-orange-400 text-2xl font-bold">+13</h2>
          <p>Años de experiencia</p>
        </div>
        <div>
          <h2 className="text-orange-400 text-2xl font-bold">+500</h2>
          <p>Proyectos</p>
        </div>
        <div>
          <h2 className="text-orange-400 text-2xl font-bold">5+</h2>
          <p>Regiones</p>
        </div>
        <div>
          <h2 className="text-orange-400 text-2xl font-bold">100%</h2>
          <p>Satisfechos</p>
        </div>
      </div>
    </section>
  );
};

export default Hero;
