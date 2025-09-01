import React from "react";
import { Button } from "@/components/ui/button";

export default function Storefront() {
  return (
    <div className="min-h-screen bg-gradient-to-b from-white to-slate-50 text-slate-900">
      {/* Topbar */}
      <header className="sticky top-0 z-40 backdrop-blur bg-white/70 border-b">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
          <div className="flex items-center gap-3">
            <div className="w-9 h-9 rounded-2xl bg-slate-900 text-white grid place-items-center font-bold">Vx</div>
            <span className="font-extrabold text-xl tracking-tight">VitrineX</span>
          </div>
          <div className="flex items-center gap-2">
            <Button size="sm" disabled>Carrinho</Button>
          </div>
        </div>
      </header>

      {/* Hero */}
      <section className="relative overflow-hidden">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
          <div className="grid md:grid-cols-2 gap-10 items-center">
            <div>
              <h1 className="text-4xl md:text-5xl font-extrabold tracking-tight">
                Sua nova loja online, simples e poderosa
              </h1>
              <p className="mt-4 text-slate-600 text-lg">
                Cadastre produtos, receba pagamentos e entregue com confiança. Tudo em uma única página moderna.
              </p>
              <div className="mt-6 flex flex-wrap gap-3">
                <Button size="lg" disabled>Ver produtos</Button>
              </div>
            </div>
            <div className="relative">
              <img
                src="https://images.unsplash.com/photo-1557821552-17105176677c?q=80&w=1600&auto=format&fit=crop"
                alt="Loja online"
                className="rounded-3xl shadow-2xl"
              />
            </div>
          </div>
        </div>
      </section>

      {/* Seção de Produtos */}
      <section id="produtos" className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10 text-center">
        <h2 className="text-2xl font-bold tracking-tight">Produtos em destaque</h2>
        <p className="mt-4 text-slate-500">Nenhum produto disponível no momento.</p>
      </section>

      {/* CTA */}
      <section className="bg-slate-900 text-white">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 grid md:grid-cols-2 gap-10 items-center">
          <div>
            <h3 className="text-3xl font-extrabold tracking-tight">Pronto para vender hoje?</h3>
            <p className="mt-3 text-slate-300">
              Este é um template React + Tailwind pronto para você personalizar com seus produtos reais e integrar com seu meio de pagamento favorito.
            </p>
          </div>
          <div className="flex md:justify-end items-center gap-3">
            <Button size="lg" variant="secondary">Começar agora</Button>
          </div>
        </div>
      </section>

      {/* Rodapé */}
      <footer className="border-t">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10 grid md:grid-cols-4 gap-8 text-sm">
          <div>
            <div className="font-extrabold text-lg">VitrineX</div>
            <p className="mt-2 text-slate-600">Seu ponto de partida para vender online com estilo e performance.</p>
          </div>
        </div>
        <div className="text-center text-xs text-slate-500 pb-8">© {new Date().getFullYear()} VitrineX. Todos os direitos reservados.</div>
      </footer>
    </div>
  );
}
