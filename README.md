<title>BrandPulse | Comunicación para Emprendedores</title> <script src="https://cdn.tailwindcss.com"></script> <script src="https://unpkg.com/lucide@latest"></script> <style> @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap'); body { font-family: 'Inter', sans-serif; } .glass { background: rgba(255, 255, 255, 0.05); backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1); } .perspective { perspective: 1000px; } .preserve-3d { transform-style: preserve-3d; transition: transform 0.6s; } .flip-card:hover .preserve-3d { transform: rotateY(180deg); } .backface-hidden { backface-visibility: hidden; } .rotate-y-180 { transform: rotateY(180deg); } </style>
<!-- 1. HERO SECTION -->
<section class="relative pt-24 pb-32 px-6">
    <div class="absolute top-0 left-1/2 -translate-x-1/2 w-full max-w-[800px] h-[600px] bg-purple-600/20 blur-[120px] rounded-full -z-10"></div>
    <div class="max-w-6xl mx-auto text-center">
        <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-white/5 border border-white/10 mb-8">
            <i data-lucide="rocket" class="w-4 h-4 text-purple-400"></i>
            <span class="text-sm font-medium tracking-wide uppercase">Potencia tu emprendimiento</span>
        </div>
        <h1 class="text-5xl md:text-7xl font-extrabold mb-6 leading-tight bg-gradient-to-r from-white via-purple-200 to-purple-400 bg-clip-text text-transparent">
            Conecta con tus clientes: <br> Comunicación de Mercados
        </h1>
        <p class="text-xl md:text-2xl text-slate-400 max-w-3xl mx-auto leading-relaxed">
            La comunicación estratégica no es solo hablar; es el puente que transforma un producto en una marca inolvidable.
        </p>
    </div>
</section>

<!-- 2. INTRODUCCIÓN -->
<section class="py-20 px-6 bg-slate-800/50">
    <div class="max-w-4xl mx-auto grid md:grid-cols-2 gap-12 items-center">
        <div>
            <h2 class="text-3xl font-bold mb-6">¿Qué es la CIM?</h2>
            <p class="text-slate-300 mb-6 text-lg">
                La <strong>Comunicación Integrada de Mercados (CIM)</strong> es el arte de coordinar todos tus mensajes para que tu marca se sienta profesional y coherente en cualquier lugar.
            </p>
            <button onclick="document.getElementById('eras').scrollIntoView({behavior:'smooth'})" class="px-6 py-3 bg-purple-600 rounded-xl font-bold hover:bg-purple-500 transition-all">Descubrir más</button>
        </div>
        <div class="glass p-8 rounded-3xl">
            <h3 class="text-xl font-bold mb-4 flex items-center gap-2">
                <i data-lucide="users" class="text-purple-400"></i> Mini Encuesta
            </h3>
            <div id="survey-box" class="space-y-3">
                <button onclick="completeSurvey()" class="w-full text-left p-4 rounded-xl bg-white/5 hover:bg-white/10 border border-white/5 text-sm transition-all">Publico solo cuando tengo tiempo</button>
                <button onclick="completeSurvey()" class="w-full text-left p-4 rounded-xl bg-white/5 hover:bg-white/10 border border-white/5 text-sm transition-all">Uso solo redes sociales</button>
                <button onclick="completeSurvey()" class="w-full text-left p-4 rounded-xl bg-white/5 hover:bg-white/10 border border-white/5 text-sm transition-all">No tengo un plan claro todavía</button>
            </div>
        </div>
    </div>
</section>

<!-- 3. LAS ERAS (Versión Simplificada para HTML) -->
<section id="eras" class="py-24 px-6">
    <div class="max-w-6xl mx-auto text-center mb-16">
        <h2 class="text-4xl font-bold mb-4">Las 6 Eras del Marketing</h2>
        <p class="text-slate-400">La evolución de cómo nos conectamos.</p>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <!-- Era 1 -->
        <div class="glass p-8 rounded-3xl border-t-4 border-purple-500">
            <span class="text-purple-400 font-bold">1ra Era</span>
            <h4 class="text-xl font-bold mt-2 mb-4">Producto</h4>
            <p class="text-slate-400 text-sm">Foco en la fabricación y calidad técnica. "Tengo este producto, cómpralo".</p>
        </div>
        <!-- Era 2 -->
        <div class="glass p-8 rounded-3xl border-t-4 border-blue-500">
            <span class="text-blue-400 font-bold">2da Era</span>
            <h4 class="text-xl font-bold mt-2 mb-4">Cliente</h4>
            <p class="text-slate-400 text-sm">Satisfacción y retención. Entendemos que el cliente tiene opciones.</p>
        </div>
        <!-- Era 3 -->
        <div class="glass p-8 rounded-3xl border-t-4 border-green-500">
            <span class="text-green-400 font-bold">3ra Era</span>
            <h4 class="text-xl font-bold mt-2 mb-4">Persona</h4>
            <p class="text-slate-400 text-sm">Valores y propósito. El cliente busca marcas con corazón.</p>
        </div>
        <!-- Era 4 -->
        <div class="glass p-8 rounded-3xl border-t-4 border-pink-500">
            <span class="text-pink-400 font-bold">4ta Era</span>
            <h4 class="text-xl font-bold mt-2 mb-4">Comunidad</h4>
            <p class="text-slate-400 text-sm">Conectividad social y recomendaciones en redes.</p>
        </div>
        <!-- Era 5 -->
        <div class="glass p-8 rounded-3xl border-t-4 border-orange-500">
            <span class="text-orange-400 font-bold">5ta Era</span>
            <h4 class="text-xl font-bold mt-2 mb-4">Datos</h4>
            <p class="text-slate-400 text-sm">Personalización masiva basada en comportamiento real.</p>
        </div>
        <!-- Era 6 -->
        <div class="glass p-8 rounded-3xl border-t-4 border-cyan-500">
            <span class="text-cyan-400 font-bold">6ta Era</span>
            <h4 class="text-xl font-bold mt-2 mb-4">IA</h4>
            <p class="text-slate-400 text-sm">Inteligencia predictiva que anticipa necesidades.</p>
        </div>
    </div>
</section>

<!-- 4. PLAN DE COMUNICACIÓN -->
<section class="py-24 px-6 bg-slate-900">
    <div class="max-w-6xl mx-auto flex flex-col md:flex-row gap-16 items-center">
        <div class="md:w-1/2">
            <h2 class="text-4xl font-bold mb-8">El Método Científico</h2>
            <div class="space-y-6">
                <div class="flex gap-4">
                    <div class="w-8 h-8 rounded bg-purple-600 flex-shrink-0 flex items-center justify-center font-bold text-sm">1</div>
                    <p class="text-slate-300"><strong class="text-white">Diagnóstico:</strong> Define el problema real del cliente.</p>
                </div>
                <div class="flex gap-4">
                    <div class="w-8 h-8 rounded bg-purple-600 flex-shrink-0 flex items-center justify-center font-bold text-sm">2</div>
                    <p class="text-slate-300"><strong class="text-white">Hipótesis:</strong> Establece metas claras (SMART).</p>
                </div>
                <div class="flex gap-4">
                    <div class="w-8 h-8 rounded bg-purple-600 flex-shrink-0 flex items-center justify-center font-bold text-sm">3</div>
                    <p class="text-slate-300"><strong class="text-white">Acción:</strong> Ejecuta tu mensaje en los canales clave.</p>
                </div>
                <div class="flex gap-4">
                    <div class="w-8 h-8 rounded bg-purple-600 flex-shrink-0 flex items-center justify-center font-bold text-sm">4</div>
                    <p class="text-slate-300"><strong class="text-white">Medición:</strong> Analiza si tu hipótesis fue correcta.</p>
                </div>
            </div>
        </div>
        <div class="md:w-1/2 w-full glass p-10 rounded-[40px]">
            <div id="sim-content">
                <p class="italic text-cyan-400 mb-4">"Siento que nadie ve mis productos..."</p>
                <button onclick="nextSim()" class="w-full p-4 bg-white/10 rounded-xl font-bold flex justify-between items-center hover:bg-white/20 transition-all">
                    Crear Estrategia <i data-lucide="arrow-right" class="w-4 h-4"></i>
                </button>
            </div>
        </div>
    </div>
</section>

<!-- 5. TIPS INTERACTIVOS -->
<section class="py-24 px-6">
    <h2 class="text-3xl font-bold text-center mb-12">Tips para Emprendedores</h2>
    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 max-w-6xl mx-auto">
        <!-- Card -->
        <div class="flip-card h-64 perspective">
            <div class="preserve-3d relative w-full h-full cursor-pointer">
                <div class="backface-hidden absolute inset-0 glass p-8 rounded-3xl flex flex-col items-center justify-center text-center">
                    <i data-lucide="heart" class="w-12 h-12 text-pink-500 mb-4"></i>
                    <h4 class="font-bold">Marca Auténtica</h4>
                </div>
                <div class="rotate-y-180 backface-hidden absolute inset-0 bg-pink-600 p-8 rounded-3xl flex items-center justify-center text-center">
                    <p class="text-sm font-medium">"Muestra quién eres. Si eres tú quien fabrica el producto, ¡muéstrate en cámara!"</p>
                </div>
            </div>
        </div>
         <!-- Card 2 -->
         <div class="flip-card h-64 perspective">
            <div class="preserve-3d relative w-full h-full cursor-pointer">
                <div class="backface-hidden absolute inset-0 glass p-8 rounded-3xl flex flex-col items-center justify-center text-center">
                    <i data-lucide="message-circle" class="w-12 h-12 text-blue-500 mb-4"></i>
                    <h4 class="font-bold">Escucha Activa</h4>
                </div>
                <div class="rotate-y-180 backface-hidden absolute inset-0 bg-blue-600 p-8 rounded-3xl flex items-center justify-center text-center">
                    <p class="text-sm font-medium">"Tus clientes te dicen qué quieren en los comentarios. ¡Léelos siempre!"</p>
                </div>
            </div>
        </div>
         <!-- Card 3 -->
         <div class="flip-card h-64 perspective">
            <div class="preserve-3d relative w-full h-full cursor-pointer">
                <div class="backface-hidden absolute inset-0 glass p-8 rounded-3xl flex flex-col items-center justify-center text-center">
                    <i data-lucide="zap" class="w-12 h-12 text-yellow-500 mb-4"></i>
                    <h4 class="font-bold">Constancia</h4>
                </div>
                <div class="rotate-y-180 backface-hidden absolute inset-0 bg-yellow-600 p-8 rounded-3xl flex items-center justify-center text-center text-slate-900">
                    <p class="text-sm font-bold">"Es mejor publicar 3 veces por semana siempre, que 10 veces en un día y luego desaparecer."</p>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- 6. RETO FINAL -->
<section class="py-24 px-6 bg-purple-600 mx-4 my-12 rounded-[50px] shadow-2xl">
    <div class="max-w-3xl mx-auto text-center">
        <h2 class="text-4xl font-bold mb-8">Define tu mensaje hoy</h2>
        <div class="bg-white p-8 rounded-3xl text-slate-900 text-left space-y-4">
            <input id="biz-client" type="text" placeholder="¿A quién le vendes?" class="w-full p-4 bg-slate-100 rounded-xl outline-none focus:ring-2 focus:ring-purple-500">
            <input id="biz-problem" type="text" placeholder="¿Qué problema solucionas?" class="w-full p-4 bg-slate-100 rounded-xl outline-none focus:ring-2 focus:ring-purple-500">
            <button onclick="generatePlan()" class="w-full py-4 bg-slate-900 text-white font-bold rounded-xl hover:bg-slate-800 transition-all">Generar mi Enfoque</button>
            <div id="result" class="hidden mt-6 p-6 bg-purple-50 rounded-xl border-2 border-dashed border-purple-200">
                <p id="result-text" class="text-purple-800 font-medium"></p>
            </div>
        </div>
    </div>
</section>

<footer class="py-12 text-center text-slate-500 text-sm">
    <p>&copy; 2024 BrandPulse Academy | Comunicación para Emprendedores</p>
</footer>

<script>
    // Initialize Icons
    lucide.createIcons();

    function completeSurvey() {
        document.getElementById('survey-box').innerHTML = `
            <div class="text-center py-4 animate-pulse">
                <i data-lucide="check-circle" class="w-12 h-12 text-green-400 mx-auto mb-2"></i>
                <p class="font-bold">¡Reconocerlo es el primer paso!</p>
            </div>
        `;
        lucide.createIcons();
    }

    let step = 0;
    function nextSim() {
        const content = document.getElementById('sim-content');
        step++;
        if(step === 1) {
            content.innerHTML = `<p class="mb-4 text-sm"><strong>Hipótesis:</strong> Si hago videos tutoriales, aumentaré mi confianza un 30%.</p><button onclick="nextSim()" class="w-full p-4 bg-white/10 rounded-xl font-bold">Ejecutar Acción</button>`;
        } else if(step === 2) {
            content.innerHTML = `<div class="text-center"><i data-lucide="trending-up" class="w-12 h-12 text-green-400 mx-auto mb-2"></i><p class="font-bold">¡Resultado positivo!</p><p class="text-xs text-slate-400">Lograste 50 nuevos seguidores interesados.</p></div>`;
            lucide.createIcons();
        }
    }

    function generatePlan() {
        const client = document.getElementById('biz-client').value;
        const prob = document.getElementById('biz-problem').value;
        if(!client || !prob) return;
        
        document.getElementById('result').classList.remove('hidden');
        document.getElementById('result-text').innerText = `¡Genial! Tu enfoque será ayudar a ${client} resolviendo el problema de ${prob}. Usa tu historia personal para conectar y mide cada mensaje.`;
    }
</script># MarketLab
