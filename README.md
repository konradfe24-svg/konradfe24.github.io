# konradfe24.github.io
<!DOCTYPE html>
<html lang="de" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Neorealismus vs. Konstruktivismus | Theorievergleich Internationale Beziehungen</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Inter & Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <!-- Tailwind configuration for custom fonts and colors -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        serif: ['Playfair Display', 'serif'],
                    },
                    colors: {
                        neo: {
                            50: '#f0f5fa',
                            100: '#d9e8f5',
                            600: '#2563eb', // Royal Blue for Neorealism
                            700: '#1d4ed8',
                            900: '#1e3a8a'
                        },
                        kon: {
                            50: '#fdf4f0',
                            100: '#fbe8e1',
                            600: '#ea580c', // Orange/Warm tone for Constructivism
                            700: '#c2410c',
                            900: '#7c2d12'
                        }
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-blue-500 selection:text-white">

    <header class="sticky top-0 z-50 bg-white/80 backdrop-blur-md border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <span class="font-serif font-bold text-xl tracking-tight text-slate-900">TheorieVergleich</span>
            </div>
            <nav class="hidden md:flex space-x-8 text-sm font-medium text-slate-600">
                <a href="#intro" class="hover:text-blue-600 transition-colors">Einleitung</a>
                <a href="#overview" class="hover:text-blue-600 transition-colors">Kernkonzepte</a>
                <a href="#matrix" class="hover:text-blue-600 transition-colors">Direkter Vergleich</a>
                <a href="#quiz" class="hover:text-blue-600 transition-colors">Wissenstest</a>
                <a href="#simulator" class="hover:text-blue-600 transition-colors text-blue-600 font-semibold">Krisen-Simulator</a>
            </nav>
            <div>
                <a href="#simulator" class="bg-blue-600 text-white px-4 py-2 rounded-xl text-sm font-medium hover:bg-blue-700 transition shadow-sm">
                    Simulator starten
                </a>
            </div>
        </div>
    </header>

    <section id="intro" class="relative overflow-hidden py-20 lg:py-32 bg-gradient-to-b from-white via-slate-50 to-slate-100 border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center max-w-3xl mx-auto">
                <span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-semibold bg-blue-100 text-blue-700 mb-6">
                    Internationale Beziehungen
                </span>
                <h1 class="font-serif text-4xl sm:text-5xl lg:text-6xl font-extrabold text-slate-900 tracking-tight mb-6">
                    Neorealismus vs. Konstruktivismus
                </h1>
                <p class="text-lg sm:text-xl text-slate-600 mb-10 leading-relaxed">
                    Zwei fundamentale Denkschulen der Internationalen Beziehungen im direkten Vergleich: Ist die Welt von Macht, Staatenkonkurrenz und Anarchie bestimmt, oder prägen Ideen, Normen und soziale Identitäten unser globales Zusammenleben?
                </p>
                <div class="flex flex-col sm:flex-row justify-center gap-4">
                    <a href="#simulator" class="inline-flex justify-center items-center px-6 py-3 rounded-xl bg-blue-600 text-white font-medium hover:bg-blue-700 transition shadow-lg shadow-blue-500/25">
                        Zum Krisen-Simulator &rarr;
                    </a>
                    <a href="#overview" class="inline-flex justify-center items-center px-6 py-3 rounded-xl bg-white border border-slate-300 text-slate-700 font-medium hover:bg-slate-50 transition">
                        Theorien entdecken
                    </a>
                </div>
            </div>

            <!-- Quick comparison cards banner -->
            <div class="mt-16 grid grid-cols-1 md:grid-cols-2 gap-8 max-w-5xl mx-auto">
                <div class="bg-white p-8 rounded-3xl border border-neo-100 shadow-sm relative overflow-hidden group hover:shadow-md transition">
                    <div class="absolute top-0 right-0 w-32 h-32 bg-neo-50 rounded-bl-full -z-0 group-hover:scale-110 transition-transform"></div>
                    <div class="relative z-10">
                        <span class="text-neo-600 font-bold text-xs uppercase tracking-wider bg-neo-100 px-3 py-1 rounded-full">Rationalistisch & Materialistisch</span>
                        <h3 class="font-serif text-2xl font-bold text-slate-900 mt-4 mb-2">Neorealismus</h3>
                        <p class="text-slate-600 text-sm leading-relaxed mb-4">
                            Konzentriert sich auf die Struktur des internationalen Systems, die Anarchie und das primäre Streben souveräner Staaten nach Überleben und relativer Macht.
                        </p>
                        <ul class="text-xs text-slate-500 space-y-1 font-medium">
                            <li>• Kern: Anarchie & Sicherheitsdilemma</li>
                            <li>• Akteure: Rationale Staaten</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-8 rounded-3xl border border-kon-100 shadow-sm relative overflow-hidden group hover:shadow-md transition">
                    <div class="absolute top-0 right-0 w-32 h-32 bg-kon-50 rounded-bl-full -z-0 group-hover:scale-110 transition-transform"></div>
                    <div class="relative z-10">
                        <span class="text-kon-600 font-bold text-xs uppercase tracking-wider bg-kon-100 px-3 py-1 rounded-full">Soziologisch & Idealistisch</span>
                        <h3 class="font-serif text-2xl font-bold text-slate-900 mt-4 mb-2">Konstruktivismus</h3>
                        <p class="text-slate-600 text-sm leading-relaxed mb-4">
                            Betont, dass die Welt nicht naturgegeben ist, sondern durch soziale Interaktionen, gemeinsame Werte, Normen und kollektive Identitäten geformt wird.
                        </p>
                        <ul class="text-xs text-slate-500 space-y-1 font-medium">
                            <li>• Kern: "Anarchie ist, was Staaten daraus machen"</li>
                            <li>• Akteure: Staaten, NGOs, Normunternehmer</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="overview" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="font-serif text-3xl font-bold text-slate-900 tracking-tight sm:text-4xl mb-4">
                    Die Dimensionen im Detail
                </h2>
                <p class="text-slate-600">
                    Wählen Sie eine Dimension aus, um zu sehen, wie Neorealismus und Konstruktivismus fundamental unterschiedlich darauf blicken.
                </p>

                <!-- Tab Buttons -->
                <div class="flex flex-wrap justify-center gap-2 mt-8" id="tab-buttons">
                    <button onclick="switchTab('worldview')" class="tab-btn px-5 py-2.5 rounded-xl font-medium text-sm transition bg-blue-600 text-white shadow-sm" data-target="worldview">Weltbild & Ontologie</button>
                    <button onclick="switchTab('security')" class="tab-btn px-5 py-2.5 rounded-xl font-medium text-sm transition bg-slate-100 text-slate-600 hover:bg-slate-200" data-target="security">Sicherheitsbegriff</button>
                    <button onclick="switchTab('actors')" class="tab-btn px-5 py-2.5 rounded-xl font-medium text-sm transition bg-slate-100 text-slate-600 hover:bg-slate-200" data-target="actors">Akteure & Interessen</button>
                    <button onclick="switchTab('scholars')" class="tab-btn px-5 py-2.5 rounded-xl font-medium text-sm transition bg-slate-100 text-slate-600 hover:bg-slate-200" data-target="scholars">Zentrale Vertreter</button>
                </div>
            </div>

            <!-- Tab Content Container -->
            <div class="max-w-5xl mx-auto bg-slate-50 border border-slate-200 rounded-3xl p-6 sm:p-10 shadow-sm">
                
                <!-- Tab 1: Weltbild -->
                <div id="content-worldview" class="tab-content grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="bg-white p-6 rounded-2xl border border-neo-100 shadow-sm">
                        <div class="flex items-center space-x-3 mb-4">
                            <span class="w-8 h-8 rounded-lg bg-neo-100 text-neo-600 flex items-center justify-center font-bold text-sm">NR</span>
                            <h3 class="font-serif text-xl font-bold text-slate-900">Neorealistisches Weltbild</h3>
                        </div>
                        <p class="text-slate-600 text-sm leading-relaxed mb-4">
                            Das internationale System ist durch eine fundamentale <strong>Anarchie</strong> gekennzeichnet – es gibt keine übergeordnete Weltregierung oder Instanz, die Recht durchsetzen kann. Daher herrscht ständiger Zwang zur Selbsthilfe (Self-Help).
                        </p>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Macht (insb. militärische und ökonomische Fähigkeiten) ist die wichtigste Währung. Kooperation ist schwierig, weil Staaten stets fürchten müssen, dass Partner betrügen oder mächtiger werden (relative Gewinne).
                        </p>
                    </div>

                    <div class="bg-white p-6 rounded-2xl border border-kon-100 shadow-sm">
                        <div class="flex items-center space-x-3 mb-4">
                            <span class="w-8 h-8 rounded-lg bg-kon-100 text-kon-600 flex items-center justify-center font-bold text-sm">KO</span>
                            <h3 class="font-serif text-xl font-bold text-slate-900">Konstruktivistisches Weltbild</h3>
                        </div>
                        <p class="text-slate-600 text-sm leading-relaxed mb-4">
                            Die Realität ist sozial konstruiert. Anarchie ist keine unveränderliche physikalische Gesetzmäßigkeit, sondern das Produkt menschlicher Praxis und Interaktion. Berühmt wurde Alexander Wendts Satz: <strong>"Anarchie ist, was Staaten daraus machen."</strong>
                        </p>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Ideen, gemeinsame Überzeugungen, kulturelle Normen und kollektive Identitäten bestimmen, wie Staaten ihre Interessen definieren und auf andere blicken (z. B. warum Atomwaffen von Nordkorea als bedrohlich, von Großbritannien aber ignoriert werden).
                        </p>
                    </div>
                </div>

                <!-- Tab 2: Sicherheitsbegriff -->
                <div id="content-security" class="tab-content hidden grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="bg-white p-6 rounded-2xl border border-neo-100 shadow-sm">
                        <div class="flex items-center space-x-3 mb-4">
                            <span class="w-8 h-8 rounded-lg bg-neo-100 text-neo-600 flex items-center justify-center font-bold text-sm">NR</span>
                            <h3 class="font-serif text-xl font-bold text-slate-900">Militärische Sicherheit & Dilemma</h3>
                        </div>
                        <p class="text-slate-600 text-sm leading-relaxed mb-4">
                            Sicherheit wird primär militärisch verstanden. Staaten befinden sich im sogenannten <strong>Sicherheitsdilemma</strong>: Rüstet ein Staat zur eigenen Verteidigung auf, empfindet der Nachbar dies als Bedrohung und rüstet ebenfalls auf – das Resultat ist weniger Sicherheit für alle trotz höherer Rüstungsausgaben.
                        </p>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Fokus liegt auf Abschreckung, Bündnissen und Machtbalancen (Balance of Power).
                        </p>
                    </div>

                    <div class="bg-white p-6 rounded-2xl border border-kon-100 shadow-sm">
                        <div class="flex items-center space-x-3 mb-4">
                            <span class="w-8 h-8 rounded-lg bg-kon-100 text-kon-600 flex items-center justify-center font-bold text-sm">KO</span>
                            <h3 class="font-serif text-xl font-bold text-slate-900">Soziale Sicherheit & Vertrauen</h3>
                        </div>
                        <p class="text-slate-600 text-sm leading-relaxed mb-4">
                            Sicherheit ist formbar und hängt von den herrschenden Beziehungen ab. Staaten können sich in eine <strong>Sicherheitsgemeinschaft</strong> (z. B. die NATO oder EU-Staaten untereinander) entwickeln, in der kriegerische Konflikte undenkbar werden, weil gemeinsame Werte und Vertrauen existieren.
                        </p>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Nicht nur physische Gewalt zählt, sondern auch menschliche Sicherheit (Human Security), Identitätsbedrohungen und diskursive Sicherheitskonstruktionen ("Securitization").
                        </p>
                    </div>
                </div>

                <!-- Tab 3: Akteure -->
                <div id="content-actors" class="tab-content hidden grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="bg-white p-6 rounded-2xl border border-neo-100 shadow-sm">
                        <div class="flex items-center space-x-3 mb-4">
                            <span class="w-8 h-8 rounded-lg bg-neo-100 text-neo-600 flex items-center justify-center font-bold text-sm">NR</span>
                            <h3 class="font-serif text-xl font-bold text-slate-900">Der Staat als unitärer Akteur</h3>
                        </div>
                        <p class="text-slate-600 text-sm leading-relaxed mb-4">
                            Der Staat wird als rationaler, in sich geschlossener ("unitary") Hauptakteur betrachtet ("Black Box"-Ansatz). Innenpolitische Strukturen, Regimetypen oder individuelle Politiker spielen kaum eine Rolle; entscheidend ist die Position im internationalen Machtgefälle.
                        </p>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Primäres Handlungsziel: Überleben und Machterhalt.
                        </p>
                    </div>

                    <div class="bg-white p-6 rounded-2xl border border-kon-100 shadow-sm">
                        <div class="flex items-center space-x-3 mb-4">
                            <span class="w-8 h-8 rounded-lg bg-kon-100 text-kon-600 flex items-center justify-center font-bold text-sm">KO</span>
                            <h3 class="font-serif text-xl font-bold text-slate-900">Vielfältige Akteure & Normen</h3>
                        </div>
                        <p class="text-slate-600 text-sm leading-relaxed mb-4">
                            Zwar sind Staaten wichtig, aber keineswegs die einzigen Akteure. Internationale Organisationen (IOs), NGOs, transnationale Netzwerke und sogenannte <strong>Normunternehmer</strong> (Norm Entrepreneurs) prägen die Agenda maßgeblich.
                        </p>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Interessen sind nicht objektiv gegeben, sondern verändern sich durch Lernprozesse, veränderte Identitäten und soziale Interaktion im Zeitverlauf.
                        </p>
                    </div>
                </div>

                <!-- Tab 4: Vertreter -->
                <div id="content-scholars" class="tab-content hidden grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="bg-white p-6 rounded-2xl border border-neo-100 shadow-sm">
                        <div class="flex items-center space-x-3 mb-4">
                            <span class="w-8 h-8 rounded-lg bg-neo-100 text-neo-600 flex items-center justify-center font-bold text-sm">NR</span>
                            <h3 class="font-serif text-xl font-bold text-slate-900">Prägende Neorealisten</h3>
                        </div>
                        <ul class="space-y-3 text-slate-600 text-sm">
                            <li class="bg-slate-50 p-3 rounded-xl border border-slate-100">
                                <strong>Kenneth Waltz:</strong> Begründer des Neorealismus (Struktureller Realismus), Autor von <em>Theory of International Politics</em> (1979).
                            </li>
                            <li class="bg-slate-50 p-3 rounded-xl border border-slate-100">
                                <strong>John Mearsheimer:</strong> Vertreter des Offensiven Realismus; argumentiert, dass Staaten stets nach Hegemonie streben müssen, um sicher zu sein.
                            </li>
                        </ul>
                    </div>

                    <div class="bg-white p-6 rounded-2xl border border-kon-100 shadow-sm">
                        <div class="flex items-center space-x-3 mb-4">
                            <span class="w-8 h-8 rounded-lg bg-kon-100 text-kon-600 flex items-center justify-center font-bold text-sm">KO</span>
                            <h3 class="font-serif text-xl font-bold text-slate-900">Prägende Konstruktivisten</h3>
                        </div>
                        <ul class="space-y-3 text-slate-600 text-sm">
                            <li class="bg-slate-50 p-3 rounded-xl border border-slate-100">
                                <strong>Alexander Wendt:</strong> Schlüsselfigur des IR-Konstruktivismus, bekannt für den berühmten Aufsatz <em>"Anarchy is what States make of it"</em> (1992).
                            </li>
                            <li class="bg-slate-50 p-3 rounded-xl border border-slate-100">
                                <strong>Martha Finnemore & Kathryn Sikkink:</strong> Pionierinnen der Normenforschung; zeigten, wie internationale Normen das Verhalten von Staaten lenken.
                            </li>
                        </ul>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <section id="matrix" class="py-20 bg-slate-100 border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-xs font-semibold uppercase tracking-wider text-blue-600 bg-blue-100 px-3 py-1 rounded-full">Direktvergleich</span>
                <h2 class="font-serif text-3xl font-bold text-slate-900 mt-4 mb-4">
                    Die Theorien im direkten Raster
                </h2>
                <p class="text-slate-600">
                    Eine kompakte Übersicht der Kernkategorien im direkten Kontrast.
                </p>
            </div>

            <!-- Comparison Table / Cards Grid -->
            <div class="max-w-5xl mx-auto bg-white rounded-3xl border border-slate-200 shadow-sm overflow-hidden">
                <div class="grid grid-cols-3 bg-slate-900 text-white p-6 text-sm sm:text-base font-semibold">
                    <div>Kategorie</div>
                    <div class="text-blue-400">Neorealismus</div>
                    <div class="text-orange-400">Konstruktivismus</div>
                </div>

                <div class="divide-y divide-slate-100 text-sm sm:text-base">
                    <!-- Row 1 -->
                    <div class="grid grid-cols-3 p-6 items-center hover:bg-slate-50 transition">
                        <div class="font-semibold text-slate-700">Theoretische Basis</div>
                        <div class="text-slate-600">Rationalismus, Materialismus, Positivismus</div>
                        <div class="text-slate-600">Soziologischer Institutionalismus, Interpretativismus</div>
                    </div>
                    <!-- Row 2 -->
                    <div class="grid grid-cols-3 p-6 items-center hover:bg-slate-50 transition">
                        <div class="font-semibold text-slate-700">Natur der Anarchie</div>
                        <div class="text-slate-600">Unveränderliche Struktur des Systems (Zwang zur Selbsthilfe)</div>
                        <div class="text-slate-600">Sozial konstruiert ("was Staaten daraus machen")</div>
                    </div>
                    <!-- Row 3 -->
                    <div class="grid grid-cols-3 p-6 items-center hover:bg-slate-50 transition">
                        <div class="font-semibold text-slate-700">Wichtigste Triebfeder</div>
                        <div class="text-slate-600">Machtverteilung & relatives Sicherheitsstreben</div>
                        <div class="text-slate-600">Ideen, Werte, Normen & kollektive Identitäten</div>
                    </div>
                    <!-- Row 4 -->
                    <div class="grid grid-cols-3 p-6 items-center hover:bg-slate-50 transition">
                        <div class="font-semibold text-slate-700">Sicht auf Wandel</div>
                        <div class="text-slate-600">Eher statisch (Wandel nur durch Verschiebung der Machtverteilung)</div>
                        <div class="text-slate-600">Dynamisch (Wandel durch Diskurs, neue Normen und Lernprozesse)</div>
                    </div>
                    <!-- Row 5 -->
                    <div class="grid grid-cols-3 p-6 items-center hover:bg-slate-50 transition">
                        <div class="font-semibold text-slate-700">Hauptkritikpunkt</div>
                        <div class="text-slate-600">Kann friedliche Kooperation (z. B. EU) oder das Ende des Kalten Krieges kaum erklären.</div>
                        <div class="text-slate-600">Wird oft als zu idealistisch oder vage in der Analyse materieller Zwänge kritisiert.</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="quiz" class="py-20 bg-white border-t border-slate-200">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <span class="text-xs font-semibold uppercase tracking-wider text-emerald-600 bg-emerald-100 px-3 py-1 rounded-full">Wissenstest</span>
                <h2 class="font-serif text-3xl font-bold text-slate-900 mt-4 mb-2">
                    Welche Theorie spricht hier?
                </h2>
                <p class="text-slate-600 text-sm sm:text-base">
                    Teste dein Verständnis: Ordne die folgenden Aussagen dem Neorealismus oder dem Konstruktivismus zu.
                </p>
            </div>

            <!-- Quiz Container -->
            <div id="quiz-container" class="bg-slate-50 border border-slate-200 rounded-3xl p-6 sm:p-10 shadow-sm">
                <div class="flex justify-between items-center mb-6 text-sm font-medium text-slate-500">
                    <span id="question-progress">Frage 1 von 4</span>
                    <span id="quiz-score" class="text-blue-600 font-bold">Punkte: 0</span>
                </div>

                <div class="mb-8">
                    <h3 id="question-text" class="font-serif text-xl sm:text-2xl font-bold text-slate-900 mb-6 leading-snug">
                        Lade Frage...
                    </h3>
                    
                    <div id="options-container" class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <!-- Options generated dynamically -->
                    </div>
                </div>

                <div id="explanation-box" class="hidden bg-white border border-slate-200 p-5 rounded-2xl mb-6">
                    <h4 id="explanation-title" class="font-bold text-base mb-1">Erklärung</h4>
                    <p id="explanation-text" class="text-slate-600 text-sm leading-relaxed"></p>
                </div>

                <div class="flex justify-end">
                    <button id="next-btn" onclick="nextQuestion()" class="hidden bg-slate-900 text-white px-6 py-3 rounded-xl font-medium text-sm hover:bg-slate-800 transition shadow-sm">
                        Nächste Frage &rarr;
                    </button>
                </div>
            </div>

            <!-- Result Card -->
            <div id="result-card" class="hidden bg-slate-50 border border-slate-200 rounded-3xl p-8 sm:p-12 text-center">
                <div class="w-16 h-16 bg-blue-100 text-blue-600 rounded-2xl flex items-center justify-center text-2xl font-bold mx-auto mb-6 shadow-sm">
                    🏆
                </div>
                <h3 class="font-serif text-2xl font-bold text-slate-900 mb-2">Quiz beendet!</h3>
                <p id="result-text" class="text-slate-600 text-base mb-8">Du hast X von 4 Fragen richtig beantwortet.</p>
                <button onclick="restartQuiz()" class="bg-blue-600 text-white px-6 py-3 rounded-xl font-medium hover:bg-blue-700 transition shadow-md">
                    Quiz wiederholen
                </button>
            </div>
        </div>
    </section>

    <section id="simulator" class="py-20 bg-slate-900 text-white border-t border-slate-800">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <span class="text-xs font-semibold uppercase tracking-wider text-amber-400 bg-amber-400/10 px-3 py-1 rounded-full">Interaktives Rollenspiel</span>
                <h2 class="font-serif text-3xl sm:text-4xl font-bold mt-4 mb-2 text-white">
                    Krisen-Simulator: Straße von Taiwan
                </h2>
                <p class="text-slate-400 text-sm sm:text-base max-w-2xl mx-auto">
                    Übernehme die Führung in einer Zuspitzung der Taiwan-Krise. Entscheide als Donald Trump (USA) oder Xi Jinping (China) und erlebe, wie Neorealismus und Konstruktivismus deine Optionen und deren Konsequenzen prägen.
                </p>
            </div>

            <!-- Simulator Wrapper -->
            <div class="bg-slate-800 border border-slate-700 rounded-3xl p-6 sm:p-10 shadow-xl">
                
                <!-- STEP 0: Role Selection with exact user portraits -->
                <div id="sim-step-role" class="space-y-6">
                    <h3 class="font-serif text-2xl font-bold text-white text-center mb-6">Wähle deine Rolle für das Szenario:</h3>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <!-- Trump Role Card -->
                        <button onclick="selectRole('trump')" class="bg-slate-900/80 border-2 border-slate-700 hover:border-blue-500 rounded-2xl p-6 text-left transition group">
                            <div class="flex items-center justify-between mb-4">
                                <span class="bg-blue-500/20 text-blue-400 font-bold text-xs px-3 py-1 rounded-full uppercase">USA Führung</span>
                                <div class="w-16 h-16 rounded-full overflow-hidden border-2 border-blue-500 shadow-md">
                                    <img src="gettyimages-2194420718-67d9b4e326598.avif" alt="Donald Trump" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="this.src='https://placehold.co/150x150/1e293b/ffffff?text=DT'">
                                </div>
                            </div>
                            <h4 class="font-serif text-xl font-bold text-white mb-2 group-hover:text-blue-400 transition">Donald Trump</h4>
                            <p class="text-slate-400 text-sm leading-relaxed">
                                Fokus auf America First, wirtschaftlichen Druck, Zölle, militärische Abschreckung und harte Machtbalance im Indopazifik.
                            </p>
                        </button>

                        <!-- Xi Role Card -->
                        <button onclick="selectRole('xi')" class="bg-slate-900/80 border-2 border-slate-700 hover:border-red-500 rounded-2xl p-6 text-left transition group">
                            <div class="flex items-center justify-between mb-4">
                                <span class="bg-red-500/20 text-red-400 font-bold text-xs px-3 py-1 rounded-full uppercase">China Führung</span>
                                <div class="w-16 h-16 rounded-full overflow-hidden border-2 border-red-500 shadow-md">
                                    <img src="Xi_Jinping_in_July_2024_(cropped).jpg" alt="Xi Jinping" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="this.src='https://placehold.co/150x150/1e293b/ffffff?text=XJ'">
                                </div>
                            </div>
                            <h4 class="font-serif text-xl font-bold text-white mb-2 group-hover:text-red-400 transition">Xi Jinping</h4>
                            <p class="text-slate-400 text-sm leading-relaxed">
                                Fokus auf historische Souveränität, nationale Identität, Wiedervereinigung als nationale Mission und Machtdemonstration vor Taiwans Küste.
                            </p>
                        </button>
                    </div>
                </div>

                <!-- Active Game Simulation Area (Hidden initially) -->
                <div id="sim-game-area" class="hidden space-y-6">
                    <!-- Status Bar -->
                    <div class="flex flex-wrap items-center justify-between bg-slate-900/70 p-4 rounded-2xl border border-slate-700 text-sm">
                        <div class="flex items-center space-x-3 mb-2 sm:mb-0">
                            <span id="sim-role-badge" class="px-3 py-1 rounded-full font-bold text-xs bg-blue-500/20 text-blue-400">Rolle</span>
                            <span id="sim-stage-indicator" class="text-slate-400">Szenario 1 von 3</span>
                        </div>
                        <div class="flex items-center space-x-6">
                            <div>Stabilität: <span id="sim-stability" class="font-bold text-emerald-400">75%</span></div>
                            <div>Orientierung: <span id="sim-tendency" class="font-bold text-blue-400">Ausgeglichen</span></div>
                        </div>
                    </div>

                    <!-- Scenario Card -->
                    <div class="bg-slate-900/90 border border-slate-700 rounded-2xl p-6 sm:p-8">
                        <h4 id="sim-scenario-title" class="font-serif text-xl sm:text-2xl font-bold text-white mb-4">Titel</h4>
                        <p id="sim-scenario-desc" class="text-slate-300 text-sm sm:text-base leading-relaxed mb-6"></p>

                        <!-- Decision Options -->
                        <div id="sim-options-container" class="space-y-4">
                            <!-- Populated dynamically -->
                        </div>
                    </div>

                    <!-- Feedback Box (Shown after selection) -->
                    <div id="sim-feedback-box" class="hidden bg-slate-900 border border-slate-700 rounded-2xl p-6">
                        <h5 id="sim-feedback-title" class="font-bold text-base mb-2 text-amber-400">Analyse & Konsequenz</h5>
                        <p id="sim-feedback-text" class="text-slate-300 text-sm leading-relaxed mb-6"></p>
                        <button onclick="nextSimScenario()" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-medium py-3 rounded-xl transition text-sm">
                            Nächster Schritt &rarr;
                        </button>
                    </div>
                </div>

                <!-- Results Summary (Hidden initially) -->
                <div id="sim-results-area" class="hidden text-center space-y-6">
                    <div class="w-16 h-16 bg-amber-400/20 text-amber-400 rounded-2xl flex items-center justify-center text-2xl font-bold mx-auto">
                        📊
                    </div>
                    <h3 class="font-serif text-2xl font-bold text-white">Simulation Abgeschlossen!</h3>
                    <p id="sim-results-summary" class="text-slate-300 text-sm sm:text-base max-w-xl mx-auto leading-relaxed"></p>
                    
                    <div class="bg-slate-900 p-6 rounded-2xl border border-slate-700 max-w-md mx-auto text-left space-y-2">
                        <div class="text-xs uppercase font-bold text-slate-400">Deine Richtungsbilanz:</div>
                        <div class="flex justify-between text-sm">
                            <span class="text-blue-400">Neorealistische Entscheidungen:</span>
                            <span id="sim-score-neo" class="font-bold">0</span>
                        </div>
                        <div class="flex justify-between text-sm">
                            <span class="text-orange-400">Konstruktivistische Entscheidungen:</span>
                            <span id="sim-score-kon" class="font-bold">0</span>
                        </div>
                    </div>

                    <button onclick="resetSimulator()" class="bg-slate-700 hover:bg-slate-600 text-white font-medium px-6 py-3 rounded-xl transition text-sm">
                        Simulation neu starten
                    </button>
                </div>

            </div>
        </div>
    </section>

    <footer class="bg-slate-950 text-slate-400 py-12 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col sm:flex-row items-center justify-between gap-4 text-sm">
            <div class="flex items-center space-x-2 text-white font-serif">
                <span>TheorieVergleich</span>
            </div>
            <p>© 2026 • Wissenschaftlicher Vergleich von Neorealismus und Konstruktivismus.</p>
            <p class="text-xs text-slate-500">Erstellt für Studierende und Interessierte der Internationalen Beziehungen.</p>
        </div>
    </footer>

    <script>
        // Tab switching function
        function switchTab(targetId) {
            document.querySelectorAll('.tab-btn').forEach(btn => {
                btn.classList.remove('bg-blue-600', 'text-white', 'shadow-sm');
                btn.classList.add('bg-slate-100', 'text-slate-600', 'hover:bg-slate-200');
            });

            const activeBtn = document.querySelector(`[data-target="${targetId}"]`);
            if(activeBtn) {
                activeBtn.classList.remove('bg-slate-100', 'text-slate-600', 'hover:bg-slate-200');
                activeBtn.classList.add('bg-blue-600', 'text-white', 'shadow-sm');
            }

            document.querySelectorAll('.tab-content').forEach(content => {
                content.classList.add('hidden');
            });

            const targetContent = document.getElementById(`content-${targetId}`);
            if(targetContent) {
                targetContent.classList.remove('hidden');
            }
        }

        // Quiz Data
        const quizData = [
            {
                question: "„Staaten müssen primär militärisch aufrüsten und Allianzen schmieden, da im anarchischen Weltsystem niemand anderes ihnen Schutz garantieren kann.“",
                options: [
                    { text: "Neorealismus", theory: "neo" },
                    { text: "Konstruktivismus", theory: "kon" }
                ],
                answer: "neo",
                explanation: "Der Neorealismus betont das Sicherheitsdilemma und den Zwang zur Selbsthilfe (Self-Help) in einem anarchischen System."
            },
            {
                question: "„Ob Atomwaffen eines Landes (z. B. Nordkorea vs. Großbritannien) als existenzielle Bedrohung wahrgenommen werden, hängt vor allem von gemeinsamen Werten, Geschichte und geteilten Identitäten ab.“",
                options: [
                    { text: "Neorealismus", theory: "neo" },
                    { text: "Konstruktivismus", theory: "kon" }
                ],
                answer: "kon",
                explanation: "Der Konstruktivismus argumentiert, dass materielle Faktoren (wie Waffen) erst durch soziale Bedeutung und geteilte Vorstellungen ihre politische Wirkung entfalten."
            },
            {
                question: "„Anarchie ist kein Naturgesetz mit festem Ausgang, sondern wird von Staaten durch ihr Handeln und ihre Diskurse stetig neu geformt.“",
                options: [
                    { text: "Neorealismus", theory: "neo" },
                    { text: "Konstruktivismus", theory: "kon" }
                ],
                answer: "kon",
                explanation: "Dies ist die Kernbotschaft von Alexander Wendts berühmtem konstruktivistischen Diktum: 'Anarchie ist, was Staaten daraus machen'."
            },
            {
                question: "„Innenpolitische Regimetypen (Demokratie oder Diktatur) spielen international kaum eine Rolle; Staaten handeln als rationale, einheitliche Akteure primär im Schatten der Machtverteilung.“",
                options: [
                    { text: "Neorealismus", theory: "neo" },
                    { text: "Konstruktivismus", theory: "kon" }
                ],
                answer: "neo",
                explanation: "Der Neorealismus verwendet den sogenannten 'Black Box'-Ansatz, bei dem das staatliche Innere vernachlässigt und nur die externe Struktur betrachtet wird."
            }
        ];

        let currentQuestionIndex = 0;
        let score = 0;
        let answered = false;

        function loadQuestion() {
            answered = false;
            const q = quizData[currentQuestionIndex];
            
            document.getElementById('question-progress').innerText = `Frage ${currentQuestionIndex + 1} von ${quizData.length}`;
            document.getElementById('quiz-score').innerText = `Punkte: ${score}`;
            document.getElementById('question-text').innerText = q.question;
            
            const optionsContainer = document.getElementById('options-container');
            optionsContainer.innerHTML = '';
            
            q.options.forEach(opt => {
                const btn = document.createElement('button');
                btn.className = "p-4 rounded-2xl border border-slate-200 bg-white font-medium text-slate-700 hover:border-blue-500 hover:bg-blue-50/50 transition text-left flex items-center justify-between group";
                btn.innerHTML = `<span>${opt.text}</span> <span class="w-6 h-6 rounded-full border border-slate-300 group-hover:border-blue-600 flex items-center justify-center text-xs text-transparent group-hover:text-blue-600">✓</span>`;
                btn.onclick = () => selectOption(opt.theory, btn);
                optionsContainer.appendChild(btn);
            });

            document.getElementById('explanation-box').classList.add('hidden');
            document.getElementById('next-btn').classList.add('hidden');
        }

        function selectOption(selectedTheory, selectedButton) {
            if (answered) return;
            answered = true;

            const q = quizData[currentQuestionIndex];
            const allButtons = document.querySelectorAll('#options-container button');

            allButtons.forEach(btn => {
                btn.disabled = true;
                const textSpan = btn.querySelector('span').innerText;
                const theoryKey = textSpan === "Neorealismus" ? "neo" : "kon";
                if(theoryKey === q.answer) {
                    btn.classList.add('border-emerald-500', 'bg-emerald-50', 'text-emerald-900');
                } else if(btn === selectedButton) {
                    btn.classList.add('border-rose-500', 'bg-rose-50', 'text-rose-900');
                }
            });

            const isCorrect = selectedTheory === q.answer;
            if (isCorrect) {
                score++;
                document.getElementById('quiz-score').innerText = `Punkte: ${score}`;
            }

            const expBox = document.getElementById('explanation-box');
            const expTitle = document.getElementById('explanation-title');
            const expText = document.getElementById('explanation-text');

            expTitle.innerText = isCorrect ? "Richtig! 🎉" : "Leider falsch.";
            expTitle.className = isCorrect ? "font-bold text-base mb-1 text-emerald-700" : "font-bold text-base mb-1 text-rose-700";
            expText.innerText = q.explanation;
            expBox.classList.remove('hidden');

            document.getElementById('next-btn').classList.remove('hidden');
        }

        function nextQuestion() {
            currentQuestionIndex++;
            if (currentQuestionIndex < quizData.length) {
                loadQuestion();
            } else {
                showResults();
            }
        }

        function showResults() {
            document.getElementById('quiz-container').classList.add('hidden');
            const resCard = document.getElementById('result-card');
            resCard.classList.remove('hidden');
            document.getElementById('result-text').innerText = `Du hast ${score} von ${quizData.length} Fragen richtig beantwortet!`;
        }

        function restartQuiz() {
            currentQuestionIndex = 0;
            score = 0;
            document.getElementById('result-card').classList.add('hidden');
            document.getElementById('quiz-container').classList.remove('hidden');
            loadQuestion();
        }

        // --- KRISEN-SIMULATOR LOGIC ---
        let simState = {
            role: null, // 'trump' or 'xi'
            stage: 0,
            stability: 75,
            neoCount: 0,
            konCount: 0
        };

        const simScenarios = {
            trump: [
                {
                    title: "Szenario 1: Die Taiwan-Halbleiter & Handelshebel",
                    description: "Chinesische Kriegsschiffe halten große Militärmanöver rund um Taiwan ab. Als US-Präsident stehst du vor der Frage, wie du ökonomisch und strategisch reagierst.",
                    options: [
                        {
                            text: "Neorealistisch: Verhängung massiver Zölle und Entsendung eines Flugzeugträgers in die Straße von Taiwan zur Machtdemonstration.",
                            type: "neo",
                            stabilityChange: -10,
                            feedback: "Neorealistische Analyse: Du setzt auf harte Machtbalance (Balance of Power) und militärische Abschreckung. China reagiert mit Wut, aber respektiert die militärische Präsenz."
                        },
                        {
                            text: "Konstruktivistisch: Einberufung eines virtuellen Gipfels zur Stärkung internationaler Normen und Verankerung gemeinsamer demokratischer Werte.",
                            type: "kon",
                            stabilityChange: +5,
                            feedback: "Konstruktivistische Analyse: Du vertraust auf diplomatischen Diskurs und Normen. China wirft dir jedoch Einmischung in innere Angelegenheiten vor; die Lage bleibt angespannt."
                        }
                    ]
                },
                {
                    title: "Szenario 2: Waffenkäufe und Sicherheitsdilemma",
                    description: "Taipeh bittet um hochmoderne Raketenabwehrsysteme. Peking warnt vor einer 'roten Linie'.",
                    options: [
                        {
                            text: "Neorealistisch: Lieferung der Waffen in Rekordzeit. Im Sicherheitsdilemma sichert nur überlegene Bewaffnung den Status quo.",
                            type: "neo",
                            stabilityChange: -15,
                            feedback: "Neorealistische Analyse: Klassisches Sicherheitsdilemma. Deine Rüstungslieferung erhöht zwar Taiwans Abschreckung, treibt aber Peking zu noch aggressiveren Manövern."
                        },
                        {
                            text: "Konstruktivistisch: Geheime Vertrauensgespräche mit Peking und Taipeh zur Etablierung neuer Kommunikationskanäle (Hotlines), um Fehlinterpretationen zu vermeiden.",
                            type: "kon",
                            stabilityChange: +10,
                            feedback: "Konstruktivistische Analyse: Durch konstruktiven Dialog und Regelvereinbarungen sinkt das Risiko eines unabsichtlichen Krieges, auch wenn Peking misstrauisch bleibt."
                        }
                    ]
                },
                {
                    title: "Szenario 3: Der diplomatische Status quo",
                    description: "Auf einem internationalen Gipfel fordert Beijing eine klare Erklärung gegen die Unabhängigkeit Taiwans.",
                    options: [
                        {
                            text: "Neorealistisch: Harte Rhetorik und strategische Zweideutigkeit beibehalten. Ein schwaches Auftreten lädt zu chinesischer Expansion ein.",
                            type: "neo",
                            stabilityChange: -5,
                            feedback: "Neorealistische Analyse: Du demonstrierst Entschlossenheit in einem anarchischen System, in dem Schwäche sofort ausgenutzt wird."
                        },
                        {
                            text: "Konstruktivistisch: Offizielle Bekräftigung des Dialogs und Betonung, dass Identitäten und Beziehungen im Wandel sind – Frieden durch gegenseitige Anerkennung.",
                            type: "kon",
                            stabilityChange: +15,
                            feedback: "Konstruktivistische Analyse: Du veränderst das narrative Klima und nimmst dem Konflikt durch Deeskalation und Kooperation den ideologischen Zündstoff."
                        }
                    ]
                }
            ],
            xi: [
                {
                    title: "Szenario 1: Der Druck auf die Seegrenze",
                    description: "Als Chinas Staatschef stehst du innenpolitisch unter Druck, die historische Einheit (Wiedervereinigung mit Taiwan) zu vollenden. Militärs fordern Manöver.",
                    options: [
                        {
                            text: "Neorealistisch: Massive Seeblockade-Übungen vor Taiwan. In der Anarchie zahlt sich Entschlossenheit und Machtausübung aus.",
                            type: "neo",
                            stabilityChange: -15,
                            feedback: "Neorealistische Analyse: Du nutzt Chinas wachsende militärische Stärke, um die Einflusssphäre im Indopazifik auszudehnen. Die USA reagieren alarmiert."
                        },
                        {
                            text: "Konstruktivistisch: Angebot eines 'Ein Land, zwei Systeme'-Kulturpakets und wirtschaftlicher Kooperation, um die gemeinsame nationale Identität zu betonen.",
                            type: "kon",
                            stabilityChange: +10,
                            feedback: "Konstruktivistische Analyse: Du setzt auf weiche Macht (Soft Power), Normen und historische Identität, stösst in Taiwan jedoch auf Skepsis."
                        }
                    ]
                },
                {
                    title: "Szenario 2: US-Waffenlieferungen an Taipeh",
                    description: "Washington liefert neue Abwehrsysteme an Taiwan. Wie reagierst du?",
                    options: [
                        {
                            text: "Neorealistisch: Verurteilung und sofortige Ausweitung von Luftraumverletzungen mit Kampffjets, um Stärke zu beweisen.",
                            type: "neo",
                            stabilityChange: -15,
                            feedback: "Neorealistische Analyse: Du antwortest mit harten militärischen Signalen, um das Kräfteverhältnis zu wahren. Die Krise eskaliert."
                        },
                        {
                            text: "Konstruktivistisch: Einladung zu einem multilateralen Wirtschaftsforum, um den Fokus von Konfrontation auf Wohlstand und gegenseitige Verflechtung zu lenken.",
                            type: "kon",
                            stabilityChange: +5,
                            feedback: "Konstruktivistische Analyse: Du versuchst, den Diskurs von militärischer Bedrohung auf wirtschaftliche Interdependenz umzulenken."
                        }
                    ]
                },
                {
                    title: "Szenario 3: Die historische Mission",
                    description: "Der Parteitag steht an. Die Frage der Souveränität über Taiwan dominiert die Debatte.",
                    options: [
                        {
                            text: "Neorealistisch: Bekräftigung, dass die Sezession notfalls mit allen militärischen Mitteln beendet wird. Hegemoniale Stärke ist nicht verhandelbar.",
                            type: "neo",
                            stabilityChange: -10,
                            feedback: "Neorealistische Analyse: Kompromisslose Machtpolitik im Sinne des strukturellen Realismus zur Durchsetzung nationaler Interessen."
                        },
                        {
                            text: "Konstruktivistisch: Betonung des langfristigen historischen Friedensprozesses und gemeinsamer kultureller Wurzeln als Basis für eine friedliche Integration.",
                            type: "kon",
                            stabilityChange: +15,
                            feedback: "Konstruktivistische Analyse: Du setzt auf langfristige Identität und soziale Integration statt auf erzwungene Unterwerfung."
                        }
                    ]
                }
            ]
        };

        function selectRole(role) {
            simState.role = role;
            simState.stage = 0;
            simState.stability = 75;
            simState.neoCount = 0;
            simState.konCount = 0;

            document.getElementById('sim-step-role').classList.add('hidden');
            document.getElementById('sim-game-area').classList.remove('hidden');

            const badge = document.getElementById('sim-role-badge');
            if (role === 'trump') {
                badge.innerText = "Rolle: Donald Trump (USA)";
                badge.className = "px-3 py-1 rounded-full font-bold text-xs bg-blue-500/20 text-blue-400";
            } else {
                badge.innerText = "Rolle: Xi Jinping (China)";
                badge.className = "px-3 py-1 rounded-full font-bold text-xs bg-red-500/20 text-red-400";
            }

            loadSimScenario();
        }

        function loadSimScenario() {
            const scenarios = simScenarios[simState.role];
            const currentScen = scenarios[simState.stage];

            document.getElementById('sim-stage-indicator').innerText = `Szenario ${simState.stage + 1} von ${scenarios.length}`;
            document.getElementById('sim-stability').innerText = `${simState.stability}%`;
            
            const tendencyEl = document.getElementById('sim-tendency');
            if (simState.neoCount > simState.konCount) {
                tendencyEl.innerText = "Neorealistisch geprägt";
                tendencyEl.className = "font-bold text-blue-400";
            } else if (simState.konCount > simState.neoCount) {
                tendencyEl.innerText = "Konstruktivistisch geprägt";
                tendencyEl.className = "font-bold text-orange-400";
            } else {
                tendencyEl.innerText = "Ausgeglichen";
                tendencyEl.className = "font-bold text-slate-300";
            }

            document.getElementById('sim-scenario-title').innerText = currentScen.title;
            document.getElementById('sim-scenario-desc').innerText = currentScen.description;

            const optContainer = document.getElementById('sim-options-container');
            optContainer.innerHTML = '';

            currentScen.options.forEach((opt) => {
                const btn = document.createElement('button');
                btn.className = "w-full text-left p-4 rounded-xl bg-slate-800 border border-slate-700 hover:border-blue-500 hover:bg-slate-750 transition text-sm text-slate-200";
                btn.innerText = opt.text;
                btn.onclick = () => makeSimDecision(opt);
                optContainer.appendChild(btn);
            });

            document.getElementById('sim-feedback-box').classList.add('hidden');
            optContainer.classList.remove('hidden');
        }

        function makeSimDecision(option) {
            if (option.type === 'neo') simState.neoCount++;
            else simState.konCount++;

            simState.stability = Math.max(10, Math.min(100, simState.stability + option.stabilityChange));

            document.getElementById('sim-options-container').classList.add('hidden');
            
            const feedbackBox = document.getElementById('sim-feedback-box');
            const feedbackTitle = document.getElementById('sim-feedback-title');
            const feedbackText = document.getElementById('sim-feedback-text');

            feedbackTitle.innerText = option.type === 'neo' ? "Neorealistische Entscheidung getroffen" : "Konstruktivistische Entscheidung getroffen";
            feedbackTitle.className = option.type === 'neo' ? "font-bold text-base mb-2 text-blue-400" : "font-bold text-base mb-2 text-orange-400";
            feedbackText.innerText = option.feedback;

            feedbackBox.classList.remove('hidden');
        }

        function nextSimScenario() {
            simState.stage++;
            const scenarios = simScenarios[simState.role];

            if (simState.stage < scenarios.length) {
                loadSimScenario();
            } else {
                showSimResults();
            }
        }

        function showSimResults() {
            document.getElementById('sim-game-area').classList.add('hidden');
            document.getElementById('sim-results-area').classList.remove('hidden');

            document.getElementById('sim-score-neo').innerText = simState.neoCount;
            document.getElementById('sim-score-kon').innerText = simState.konCount;

            let summaryText = "";
            if (simState.neoCount > simState.konCount) {
                summaryText = "Du hast überwiegend neorealistisch gehandelt! Dein Fokus lag auf Abschreckung, relativer Macht, militärischer Stärke und der Härte des Anarchiesystems. Dies hielt zwar deine Interessen gewahrt, steigerte jedoch das Sicherheitsdilemma.";
            } else if (simState.konCount > simState.neoCount) {
                summaryText = "Du hast überwiegend konstruktivistisch gehandelt! Dein Fokus lag auf Diplomatie, Vertrauensaufbau, Normen und der Veränderbarkeit von Identitäten. Du versuchtest, den Konflikt durch konstruktiven Diskurs zu entschärfen.";
            } else {
                summaryText = "Du hast einen ausgewogenen Mix aus neorealistischer Machtpolitik und konstruktivistischer Diplomatie gewählt – ein pragmatischer Realismus!";
            }

            document.getElementById('sim-results-summary').innerText = summaryText;
        }

        function resetSimulator() {
            document.getElementById('sim-results-area').classList.add('hidden');
            document.getElementById('sim-step-role').classList.remove('hidden');
        }

        window.onload = function() {
            loadQuestion();
        };
    </script>
</body>
</html>
