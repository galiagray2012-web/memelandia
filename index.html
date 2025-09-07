import React from "react";
import { motion } from "framer-motion";
import { Button } from "@/components/ui/button";
import { Card, CardContent, CardHeader, CardTitle } from "@/components/ui/card";
import { Input } from "@/components/ui/input";
import { Laugh, Menu, Star } from "lucide-react";

// === Helper components ===
const Section = ({ id, title, subtitle, children }: { id?: string; title?: string; subtitle?: string; children: React.ReactNode }) => (
  <section id={id} className="w-full max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
    {title && (
      <div className="mb-10 text-center">
        <h2 className="text-3xl sm:text-4xl font-bold tracking-tight">{title}</h2>
        {subtitle && <p className="mt-3 text-muted-foreground text-base sm:text-lg">{subtitle}</p>}
      </div>
    )}
    {children}
  </section>
);

const MemeCard = ({ title }: { title: string }) => (
  <Card className="shadow-sm hover:scale-105 transition-transform">
    <CardContent className="p-4 flex flex-col items-center justify-center">
      <div className="aspect-[4/3] w-full bg-muted rounded-lg mb-3 flex items-center justify-center">
        <span className="text-muted-foreground">{title}</span>
      </div>
      <Button variant="secondary" size="sm">Compartir 😂</Button>
    </CardContent>
  </Card>
);

// === Main page ===
export default function MemeWebsite() {
  return (
    <div className="min-h-screen bg-gradient-to-br from-yellow-100 via-pink-100 to-blue-100 text-foreground">
      {/* NAVBAR */}
      <header className="sticky top-0 z-40 w-full border-b bg-background/80 backdrop-blur">
        <nav className="max-w-6xl mx-auto flex items-center justify-between px-4 sm:px-6 lg:px-8 h-16">
          <a href="#home" className="flex items-center gap-2 font-bold text-xl">
            <Laugh className="h-6 w-6 text-pink-500" />
            <span>Memelandia</span>
          </a>
          <div className="hidden md:flex items-center gap-6 text-sm">
            <a href="#daily" className="hover:opacity-80">Meme del día</a>
            <a href="#gallery" className="hover:opacity-80">Galería</a>
            <a href="#top" className="hover:opacity-80">Top del día</a>
            <a href="#categories" className="hover:opacity-80">Categorías</a>
            <a href="#contact" className="hover:opacity-80">Contacto</a>
          </div>
          <div className="flex items-center gap-2">
            <Button variant="ghost" className="md:hidden" aria-label="Open menu">
              <Menu className="h-5 w-5" />
            </Button>
            <Button className="bg-pink-500 hover:bg-pink-600">Sube tu meme</Button>
          </div>
        </nav>
      </header>

      {/* HERO */}
      <Section id="home">
        <div className="text-center max-w-3xl mx-auto">
          <h1 className="text-5xl font-extrabold leading-tight">
            Bienvenid@ a <span className="text-pink-500">Memelandia</span>
          </h1>
          <p className="mt-4 text-lg">
            El lugar donde los memes mandan 👑. Prepárate para reír a carcajadas todos los días.
          </p>
          <Button size="lg" className="mt-6 bg-yellow-400 hover:bg-yellow-500 text-black">
            ¡Quiero reírme ya! 😂
          </Button>
        </div>
      </Section>

      {/* MEME DEL DÍA */}
      <Section id="daily" title="Meme del día" subtitle="Un nuevo meme cada 24 horas">
        <motion.div initial={{ opacity: 0, scale: 0.95 }} animate={{ opacity: 1, scale: 1 }} transition={{ duration: 0.6 }}
          className="max-w-3xl mx-auto">
          <Card className="shadow-lg border-pink-400">
            <CardHeader>
              <CardTitle className="flex items-center gap-2">
                <Star className="h-5 w-5 text-yellow-500" /> Destacado de hoy
              </CardTitle>
            </CardHeader>
            <CardContent>
              <div className="aspect-[16/9] rounded-lg bg-muted flex items-center justify-center overflow-hidden">
                <img src="https://i.imgflip.com/a5dzop.jpg" alt="Meme del día" className="object-cover w-full h-full" />
              </div>
            </CardContent>
          </Card>
        </motion.div>
      </Section>

      {/* GALLERY */}
      <Section id="gallery" title="Galería de memes" subtitle="Memes anteriores para seguir riendo">
        <div className="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
          {["Meme anterior 1", "Meme anterior 2", "Meme anterior 3", "Meme anterior 4", "Meme anterior 5", "Meme anterior 6"].map((m, i) => (
            <MemeCard key={i} title={m} />
          ))}
        </div>
      </Section>

      {/* TOP MEMES */}
      <Section id="top" title="Top memes del día" subtitle="Lo más votado por la comunidad">
        <div className="grid md:grid-cols-3 gap-6">
          {["Este meme rompió internet", "No puedo parar de reír", "Lo mejor de hoy"].map((quote, i) => (
            <Card key={i} className="shadow-md border-pink-400">
              <CardHeader>
                <CardTitle className="flex items-center gap-2">
                  <Star className="h-5 w-5 text-yellow-500" /> {quote}
                </CardTitle>
              </CardHeader>
              <CardContent>
                <div className="aspect-[4/3] rounded-lg bg-muted flex items-center justify-center">
                  <span className="text-muted-foreground">Meme top {i+1}</span>
                </div>
              </CardContent>
            </Card>
          ))}
        </div>
      </Section>

      {/* CATEGORIES */}
      <Section id="categories" title="Categorías" subtitle="Encuentra tu tipo de humor">
        <div className="grid sm:grid-cols-2 lg:grid-cols-4 gap-4">
          {["Animales 🐶", "Escuela 📚", "Famosos 🎬", "Random 🤯"].map((c, i) => (
            <Card key={i} className="shadow-sm hover:scale-105 transition-transform">
              <CardContent className="p-6 text-center font-semibold">{c}</CardContent>
            </Card>
          ))}
        </div>
      </Section>

      {/* CONTACT */}
      <Section id="contact" title="Sube tu meme" subtitle="¿Tienes un meme épico? Compártelo con nosotros">
        <Card className="shadow-sm max-w-2xl mx-auto">
          <CardHeader>
            <CardTitle>Formulario</CardTitle>
          </CardHeader>
          <CardContent>
            <form className="grid gap-4">
              <Input placeholder="Tu nombre o apodo" />
              <Input placeholder="Correo" type="email" />
              <Input placeholder="Título del meme" />
              <Input type="file" />
              <Button className="bg-pink-500 hover:bg-pink-600">Enviar meme</Button>
            </form>
          </CardContent>
        </Card>
      </Section>

      {/* FOOTER */}
      <footer className="border-t bg-background/80">
        <div className="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 py-10 flex flex-col sm:flex-row items-center justify-between gap-4">
          <p className="text-sm">© {new Date().getFullYear()} Memelandia 😂. Todos los derechos reservados.</p>
          <div className="flex items-center gap-4 text-sm">
            <a href="#" className="hover:opacity-80">Privacidad</a>
            <a href="#" className="hover:opacity-80">Términos</a>
            <a href="#" className="hover:opacity-80">Contacto</a>
          </div>
        </div>
      </footer>
    </div>
  );
}
