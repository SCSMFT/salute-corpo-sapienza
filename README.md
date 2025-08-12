# salute-corpo-sapienza
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salute Corpo Sapienza - Chinesiologia e Massofisioterapia</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .hero-gradient {
            background: linear-gradient(135deg, rgba(255,245,238,0.9) 0%, rgba(255,228,196,0.9) 100%);
        }
        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }
        .value-icon {
            transition: all 0.3s ease;
        }
        .value-card:hover .value-icon {
            transform: scale(1.1);
            color: #f59e0b;
        }
        .appointment-form {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
        }
    </style>
</head>
<body class="font-sans text-gray-800">
    <!-- Header/Navigation -->
    <header class="sticky top-0 z-50 bg-white shadow-sm">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center">
                <div class="w-12 h-12 rounded-full bg-amber-100 flex items-center justify-center mr-3">
                    <img src="https://scontent-fco2-1.xx.fbcdn.net/v/t39.30808-1/484343905_505114732668262_7429280877889826112_n.jpg?stp=dst-jpg_s480x480_tt6&_nc_cat=107&ccb=1-7&_nc_sid=2d3e12&_nc_ohc=oWm6ljPSLikQ7kNvwF_oLY2&_nc_oc=Adm9zMvikUvInsNt_Q1c4_zgQZ0f3dPvxBmFarQVKmokn9rcPPJxPJDiNfDPizOy__s&_nc_zt=24&_nc_ht=scontent-fco2-1.xx&_nc_gid=X1ku3aNYa_AQLJQXBeaGiw&oh=00_AfWXlILV3scl1fdwfthdwuAAuVa4NpAPoSXkQ9Cvn2Yu_w&oe=689FEC15" alt="Logo" class="w-full h-full rounded-full object-cover">
                </div>
                <h1 class="text-xl font-bold text-gray-800">Salute Corpo Sapienza</h1>
            </div>
            <nav class="hidden md:flex space-x-8">
                <a href="#servizi" class="text-gray-600 hover:text-amber-600 transition">Servizi</a>
                <a href="#approccio" class="text-gray-600 hover:text-amber-600 transition">Metodo</a>
                <a href="#valori" class="text-gray-600 hover:text-amber-600 transition">Valori</a>
                <a href="#contatti" class="text-gray-600 hover:text-amber-600 transition">Contatti</a>
            </nav>
            <button class="md:hidden text-gray-600" id="menu-toggle">
                <i class="fas fa-bars text-2xl"></i>
            </button>
        </div>
        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white py-4 px-4 shadow-lg">
            <a href="#servizi" class="block py-2 text-gray-600 hover:text-amber-600 transition">Servizi</a>
            <a href="#approccio" class="block py-2 text-gray-600 hover:text-amber-600 transition">Metodo</a>
            <a href="#valori" class="block py-2 text-gray-600 hover:text-amber-600 transition">Valori</a>
            <a href="#contatti" class="block py-2 text-gray-600 hover:text-amber-600 transition">Contatti</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero-gradient py-16 md:py-24">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0 md:pr-10">
                <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold text-gray-800 mb-4">Ogni gravidanza lascia un segno. Non sei solo una mamma, sei anche una donna
</h2>
                <p class="text-lg text-gray-700 mb-6">Un ricordo, una cicatrice, un cambiamento. Sono tracce di amore e di vita, ma meritano anche attenzione e cura, perché tu possa sentirti bene nel corpo che ti accompagna ogni giorno</p>
                <div class="flex flex-col sm:flex-row space-y-3 sm:space-y-0 sm:space-x-4">
                    <a href="#servizi" class="bg-amber-500 hover:bg-amber-600 text-white font-medium py-3 px-6 rounded-full transition duration-300 text-center">
                        Scopri i servizi
                    </a>
                    <a href="#contatti" class="border border-amber-500 text-amber-600 hover:bg-amber-50 font-medium py-3 px-6 rounded-full transition duration-300 text-center">
                        Prenota una consulenza
                    </a>
                </div>
            </div>
            <div class="md:w-1/2">
                <div class="bg-white p-2 rounded-2xl shadow-xl">
                    <img src="https://ucf9c5a2001c54e5ae1adf08a0ec.previews.dropboxusercontent.com/p/thumb/ACt1pSKfjT8vJGqcOYJ_45lB67uI9OA24NVTAJmhZiFXa_4k7fuYwLR-HdHihrP-1SWEtgQ8JXGk4VdM2H9RZFcAim5Xm8E1yvYW14NdL2rlq-sdLr2BAwGGXL257SbcBHE-1Np2h3tAWpX-qA2WUju3mkVa9IV3PCQ9YyTrjrBCjnS6wgjQb0tsBQbcyW11j2VRuwMboDDRatJwg4WtwW2tfrc4CVpsEGfvij0YPpBmALYrJgPZpEO6QiN6wgnVhYPrIbQjzjgsEJLGBYlq1LnWhY3Sw1mZPHCOZPZNUvv10tkpwxh0Fjbt6q0fxmn7X-3p6IrJiWF9ejRJpNZ8Gdigao2-ZSCP4Yg1zapDIw6mrc6xy3ow3Uk8dx7n1aUGsDD62Yeg4ULxQeup5AerHy71VVnpAd2iuUxjvkP9JvvkR_QevUtayuOP1O2RKLyNRBs/p.png?is_prewarmed=true"
                         alt="Silvia Concetta Sapienza al lavoro"
                         class="w-full h-auto rounded-xl object-cover">
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="servizi" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">I miei servizi</h2>
                <div class="w-20 h-1 bg-amber-500 mx-auto"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

<!-- Service 1 -->
                <div class="service-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300 p-6 border-2 border-amber-500 relative">
                    <div class="absolute top-0 right-0 bg-amber-500 text-white text-xs font-bold px-2 py-1 rounded-bl-lg rounded-tr-lg">
                        POPOLARE
                    </div>
                    <div class="w-14 h-14 rounded-full bg-amber-100 flex items-center justify-center mb-4">
                        <i class="fas fa-baby text-amber-500 text-xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3 text-gray-800">Diastasi addominale post-parto</h3>
                    <p class="text-gray-600 mb-4">Trattamento con esercizi mirati, massofisioterapia e tecniche respiratorie per ripristinare la funzionalità della parete addominale.</p>
                    <div class="flex space-x-3">
                        <a href="diastasi.html" class="inline-block bg-amber-500 hover:bg-amber-600 text-white font-medium py-2 px-4 rounded-lg transition duration-300 text-sm">
                            Scopri di più
                        </a>
                        <a href="#contatti" class="inline-block border border-amber-500 text-amber-600 hover:bg-amber-50 font-medium py-2 px-4 rounded-lg transition duration-300 text-sm">
                            Prenota ora
                        </a>
                    </div>
                </div>

                <!-- Service 2 -->
                <div class="service-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300 p-6 border border-gray-100">
                    <div class="w-14 h-14 rounded-full bg-amber-100 flex items-center justify-center mb-4">
                        <i class="fas fa-procedures text-amber-500 text-xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3 text-gray-800">Riabilitazione post-operatoria</h3>
                    <p class="text-gray-600 mb-4">Recupero funzionale dopo interventi come cesareo, addominoplastica e protesi mammarie.</p>
                    <div class="flex space-x-3">
                        <a href="/riabilitazione-post-operatoria" class="inline-block bg-amber-500 hover:bg-amber-600 text-white font-medium py-2 px-4 rounded-lg transition duration-300 text-sm">
                            Scopri di più
                        </a>
                        <a href="#contatti" class="inline-block border border-amber-500 text-amber-600 hover:bg-amber-50 font-medium py-2 px-4 rounded-lg transition duration-300 text-sm">
                            Prenota ora
                        </a>
                    </div>
                </div>

                <!-- Service 3 -->
                <div class="service-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300 p-6 border border-gray-100">
                    <div class="w-14 h-14 rounded-full bg-amber-100 flex items-center justify-center mb-4">
                        <i class="fas fa-bone text-amber-500 text-xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3 text-gray-800">Dolori muscolari e posturali</h3>
                    <p class="text-gray-600 mb-4">Terapie per contratture, dolori cervicali, lombari e muscolari cronici con approccio integrato.</p>
                    <div class="flex space-x-3">
                        <a href="/dolori-muscolari" class="inline-block bg-amber-500 hover:bg-amber-600 text-white font-medium py-2 px-4 rounded-lg transition duration-300 text-sm">
                            Scopri di più
                        </a>
                        <a href="#contatti" class="inline-block border border-amber-500 text-amber-600 hover:bg-amber-50 font-medium py-2 px-4 rounded-lg transition duration-300 text-sm">
                            Prenota ora
                        </a>
                    </div>
                </div>

                <!-- Service 4 -->
                <div class="service-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300 p-6 border border-gray-100">
                    <div class="w-14 h-14 rounded-full bg-amber-100 flex items-center justify-center mb-4">
                        <i class="fas fa-spa text-amber-500 text-xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3 text-gray-800">Trattamenti LPG Endermologie</h3>
                    <p class="text-gray-600 mb-4">Tecnologia medicale per drenaggio, trattamento di cicatrici, cellulite e rimodellamento corporeo.</p>
                    <div class="flex space-x-3">
                        <a href="/trattamenti-lpg" class="inline-block bg-amber-500 hover:bg-amber-600 text-white font-medium py-2 px-4 rounded-lg transition duration-300 text-sm">
                            Scopri di più
                        </a>
                        <a href="#contatti" class="inline-block border border-amber-500 text-amber-600 hover:bg-amber-50 font-medium py-2 px-4 rounded-lg transition duration-300 text-sm">
                            Prenota ora
                        </a>
                    </div>
                </div>

                <!-- Service 6 -->
                <div class="service-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300 p-6 border border-gray-100">
                    <div class="w-14 h-14 rounded-full bg-amber-100 flex items-center justify-center mb-4">
                        <i class="fas fa-dumbbell text-amber-500 text-xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3 text-gray-800">Fitness del pavimento pelvico</h3>
                    <p class="text-gray-600 mb-4">Rinforzo della muscolatura profonda per migliorare la funzionalità uro-ginecologica e la qualità della vita.</p>
                    <div class="flex space-x-3">
                        <a href="/fitness-pavimento-pelvico" class="inline-block bg-amber-500 hover:bg-amber-600 text-white font-medium py-2 px-4 rounded-lg transition duration-300 text-sm">
                            Scopri di più
                        </a>
                        <a href="#contatti" class="inline-block border border-amber-500 text-amber-600 hover:bg-amber-50 font-medium py-2 px-4 rounded-lg transition duration-300 text-sm">
                            Prenota ora
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Approach Section -->
    <section id="approccio" class="py-16 bg-amber-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Il mio metodo</h2>
                <div class="w-20 h-1 bg-amber-500 mx-auto"></div>
            </div>

            <div class="flex flex-col lg:flex-row items-center">
                <div class="lg:w-1/2 mb-10 lg:mb-0 lg:pr-10">
                    <img src="https://images.unsplash.com/photo-1571019614242-c95595945bbf?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80"
                         alt="Approccio terapeutico"
                         class="w-full h-auto rounded-xl shadow-lg">
                </div>
                <div class="lg:w-1/2">
                    <div class="bg-white p-8 rounded-xl shadow-sm">
                        <h3 class="text-2xl font-semibold text-gray-800 mb-4">Un metodo non invasivo e indolore.
                        <p class="text-gray-600 mb-6">Il mio lavoro si basa sulla convinzione che ogni persona meriti un percorso attento e rispettoso dei suoi tempi e delle sue esigenze.</p>

                        <div class="space-y-4">
                            <div class="flex items-start">
                                <div class="flex-shrink-0 mt-1">
                                    <div class="w-8 h-8 rounded-full bg-amber-100 flex items-center justify-center">
                                        <i class="fas fa-check text-amber-500 text-sm"></i>
                                    </div>
                                </div>
                                <div class="ml-3">
                                    <p class="text-gray-700 font-medium">Consapevolezza corporea</p>
                                    <p class="text-gray-600 text-sm">Ti guido a riconoscere e comprendere i segnali del tuo corpo per ottenere risultati duraturi.</p>
                                </div>
                            </div>

                            <div class="flex items-start">
                                <div class="flex-shrink-0 mt-1">
                                    <div class="w-8 h-8 rounded-full bg-amber-100 flex items-center justify-center">
                                        <i class="fas fa-check text-amber-500 text-sm"></i>
                                    </div>
                                </div>
                                <div class="ml-3">
                                    <p class="text-gray-700 font-medium">Obiettivi realistici</p>
                                    <p class="text-gray-600 text-sm">Niente promesse miracolose, solo progressi misurabili e sostenibili nel tempo.</p>
                                </div>
                            </div>

                            <div class="flex items-start">
                                <div class="flex-shrink-0 mt-1">
                                    <div class="w-8 h-8 rounded-full bg-amber-100 flex items-center justify-center">
                                        <i class="fas fa-check text-amber-500 text-sm"></i>
                                    </div>
                                </div>
                                <div class="ml-3">
                                    <p class="text-gray-700 font-medium">Integrazione di tecniche</p>
                                    <p class="text-gray-600 text-sm">Combino chinesiologia, massofisioterapia e tecnologie avanzate per risultati ottimali.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Values Section -->
    <section id="valori" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">I miei valori</h2>
                <div class="w-20 h-1 bg-amber-500 mx-auto"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Value 1 -->
                <div class="value-card bg-white rounded-xl shadow-sm overflow-hidden transition duration-300 p-6 border border-gray-100">
                    <div class="value-icon w-14 h-14 rounded-full bg-amber-100 flex items-center justify-center mb-4 text-amber-500 text-xl">
                        <i class="fas fa-hand-holding-heart"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3 text-gray-800">Onestà e trasparenza</h3>
                    <p class="text-gray-600">Niente promesse irrealistiche, solo soluzioni efficaci e appropriate per la tua situazione specifica.</p>
                </div>

                <!-- Value 2 -->
                <div class="value-card bg-white rounded-xl shadow-sm overflow-hidden transition duration-300 p-6 border border-gray-100">
                    <div class="value-icon w-14 h-14 rounded-full bg-amber-100 flex items-center justify-center mb-4 text-amber-500 text-xl">
                        <i class="fas fa-heart"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3 text-gray-800">Empatia e comprensione</h3>
                    <p class="text-gray-600">Ascolto autentico, attenzione ai bisogni e alle emozioni che accompagnano il percorso di guarigione.</p>
                </div>

                <!-- Value 3 -->
                <div class="value-card bg-white rounded-xl shadow-sm overflow-hidden transition duration-300 p-6 border border-gray-100">
                    <div class="value-icon w-14 h-14 rounded-full bg-amber-100 flex items-center justify-center mb-4 text-amber-500 text-xl">
                        <i class="fas fa-shield-alt"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3 text-gray-800">Prevenzione</h3>
                    <p class="text-gray-600">Promuovo esercizio e cura costante, anche a bassa intensità, per ridurre la necessità di trattamenti futuri.</p>
                </div>

                <!-- Value 4 -->
                <div class="value-card bg-white rounded-xl shadow-sm overflow-hidden transition duration-300 p-6 border border-gray-100">
                    <div class="value-icon w-14 h-14 rounded-full bg-amber-100 flex items-center justify-center mb-4 text-amber-500 text-xl">
                        <i class="fas fa-walking"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3 text-gray-800">Autonomia</h3>
                    <p class="text-gray-600">Ti accompagno fino a renderti autonoma nel gestire il tuo corpo e mantenere i risultati ottenuti.</p>
                </div>


                <!-- Value 6 -->
                <div class="value-card bg-white rounded-xl shadow-sm overflow-hidden transition duration-300 p-6 border border-gray-100">
                    <div class="value-icon w-14 h-14 rounded-full bg-amber-100 flex items-center justify-center mb-4 text-amber-500 text-xl">
                        <i class="fas fa-home"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3 text-gray-800">Accoglienza</h3>
                    <p class="text-gray-600">Ogni aspetto, anche ambientale, è pensato per farti sentire accolta e a tuo agio durante il trattamento.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="py-16 bg-amber-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Cosa dicono le pazienti</h2>
                <div class="w-20 h-1 bg-amber-500 mx-auto"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-white p-6 rounded-xl shadow-sm border border-gray-100">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 rounded-full bg-amber-100 flex items-center justify-center mr-4">
                            <i class="fas fa-user text-amber-500"></i>
                        </div>
                        <div>
                            <h4 class="font-semibold text-gray-800">Maria G.</h4>
                            <div class="flex text-amber-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">"Dopo due gravidanze ravvicinate soffrivo di diastasi addominale. Silvia mi ha aiutato a recuperare completamente con un programma su misura. Oltre alla competenza, apprezzo la sua umanità e pazienza."</p>
                </div>

                <!-- Testimonial 2 -->
                <div class="bg-white p-6 rounded-xl shadow-sm border border-gray-100">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 rounded-full bg-amber-100 flex items-center justify-center mr-4">
                            <i class="fas fa-user text-amber-500"></i>
                        </div>
                        <div>
                            <h4 class="font-semibold text-gray-800">Laura F.</h4>
                            <div class="flex text-amber-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">"La riabilitazione post-cesareo con Silvia è stata fondamentale. Mi ha insegnato esercizi che potevo fare anche a casa con il bambino. Dopo 3 mesi mi sentivo meglio che prima della gravidanza!"</p>
                </div>

                <!-- Testimonial 3 -->
                <div class="bg-white p-6 rounded-xl shadow-sm border border-gray-100">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 rounded-full bg-amber-100 flex items-center justify-center mr-4">
                            <i class="fas fa-user text-amber-500"></i>
                        </div>
                        <div>
                            <h4 class="font-semibold text-gray-800">Elena R.</h4>
                            <div class="flex text-amber-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">"Soffrivo di dolori cervicali cronici. Con Silvia ho capito che la causa era la mia postura. Oltre alle sedute, mi ha dato strumenti per correggermi durante la giornata. Finalmente posso lavorare senza dolore."</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contatti" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Contattami</h2>
                <div class="w-20 h-1 bg-amber-500 mx-auto"></div>
            </div>

            <div class="flex flex-col lg:flex-row">
                <div class="lg:w-1/2 mb-10 lg:mb-0 lg:pr-10">
                    <div class="bg-amber-50 p-8 rounded-xl h-full">
                        <h3 class="text-2xl font-semibold text-gray-800 mb-6">Informazioni e prenotazioni</h3>

                        <div class="space-y-6">
                            <div class="flex items-start">
                                <div class="flex-shrink-0 mt-1">
                                    <div class="w-10 h-10 rounded-full bg-amber-100 flex items-center justify-center">
                                        <i class="fas fa-map-marker-alt text-amber-500"></i>
                                    </div>
                                </div>
                                <div class="ml-4">
                                    <h4 class="font-medium text-gray-800">Studio</h4>
                                    <p class="text-gray-600">Via Roma, 20 – Viagrande (CT)</p>
                                </div>
                            </div>

                            <div class="flex items-start">
                                <div class="flex-shrink-0 mt-1">
                                    <div class="w-10 h-10 rounded-full bg-amber-100 flex items-center justify-center">
                                        <i class="fas fa-phone-alt text-amber-500"></i>
                                    </div>
                                </div>
                                <div class="ml-4">
                                    <h4 class="font-medium text-gray-800">Telefono</h4>
                                    <p class="text-gray-600">376.1543999</p>
                                </div>
                            </div>

                            <div class="flex items-start">
                                <div class="flex-shrink-0 mt-1">
                                    <div class="w-10 h-10 rounded-full bg-amber-100 flex items-center justify-center">
                                        <i class="fas fa-clock text-amber-500"></i>
                                    </div>
                                </div>
                                <div class="ml-4">
                                    <h4 class="font-medium text-gray-800">Orari</h4>
                                    <p class="text-gray-600">Ricevo su appuntamento</p>
                                </div>
                            </div>
                        </div>

                        <div class="mt-8">
                            <h4 class="font-medium text-gray-800 mb-3">Come raggiungermi</h4>
                            <div class="aspect-w-16 aspect-h-9 rounded-xl overflow-hidden">
                                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3159.869328373644!2d15.09667731531638!3d37.61897997978406!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1313fcd2c25e2457%3A0x3c1a43d3e0e3b3b4!2sVia%20Roma%2C%2020%2C%2095029%20Viagrande%20CT!5e0!3m2!1sen!2sit!4v1623256789012!5m2!1sen!2sit"
                                        width="100%"
                                        height="300"
                                        style="border:0;"
                                        allowfullscreen=""
                                        loading="lazy"
                                        class="rounded-xl"></iframe>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="lg:w-1/2">
                    <div class="appointment-form p-8 rounded-xl shadow-sm border border-gray-100">
                        <h3 class="text-2xl font-semibold text-gray-800 mb-6">Prenota una consulenza</h3>

                        <form id="contact-form" class="space-y-4">
                            <div>
                                <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Nome e cognome</label>
                                <input type="text" id="name" name="name" required
                                       class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-amber-500 focus:border-amber-500 transition">
                            </div>

                            <div>
                                <label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email</label>
                                <input type="email" id="email" name="email" required
                                       class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-amber-500 focus:border-amber-500 transition">
                            </div>

                            <div>
                                <label for="phone" class="block text-sm font-medium text-gray-700 mb-1">Telefono</label>
                                <input type="tel" id="phone" name="phone" required
                                       class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-amber-500 focus:border-amber-500 transition">
                            </div>

                            <div>
                                <label for="service" class="block text-sm font-medium text-gray-700 mb-1">Servizio di interesse</label>
                                <select id="service" name="service"
                                        class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-amber-500 focus:border-amber-500 transition">
                                    <option value="">Seleziona un servizio</option>
                                    <option value="diastasi">Diastasi addominale post-parto</option>
                                    <option value="riabilitazione">Riabilitazione post-operatoria</option>
                                    <option value="dolori">Dolori muscolari e posturali</option>
                                    <option value="lpg">Trattamenti LPG Endermologie</option>
                                    <option value="posturale">Educazione posturale e respiratoria</option>
                                    <option value="pelvico">Fitness del pavimento pelvico</option>
                                </select>
                            </div>

                            <div>
                                <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Messaggio</label>
                                <textarea id="message" name="message" rows="4"
                                          class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-amber-500 focus:border-amber-500 transition"></textarea>
                            </div>

                            <button type="submit"
                                    class="w-full bg-amber-500 hover:bg-amber-600 text-white font-medium py-3 px-6 rounded-lg transition duration-300 mt-4">
                                Invia richiesta
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-6 md:mb-0">
                    <div class="flex items-center">
                        <div class="w-10 h-10 rounded-full bg-amber-100 flex items-center justify-center mr-3">
                            <img src="https://scontent-fco2-1.xx.fbcdn.net/v/t39.30808-1/484343905_505114732668262_7429280877889826112_n.jpg?stp=dst-jpg_s480x480_tt6&_nc_cat=107&ccb=1-7&_nc_sid=2d3e12&_nc_ohc=oWm6ljPSLikQ7kNvwF_oLY2&_nc_oc=Adm9zMvikUvInsNt_Q1c4_zgQZ0f3dPvxBmFarQVKmokn9rcPPJxPJDiNfDPizOy__s&_nc_zt=24&_nc_ht=scontent-fco2-1.xx&_nc_gid=X1ku3aNYa_AQLJQXBeaGiw&oh=00_AfWXlILV3scl1fdwfthdwuAAuVa4NpAPoSXkQ9Cvn2Yu_w&oe=689FEC15" alt="Logo" class="w-full h-full rounded-full object-cover">
                        </div>
                        <h3 class="text-xl font-bold">Silvia Concetta Sapienza</h3>
                    </div>
                    <p class="text-gray-400 mt-2">Chinesiologa e Massofisioterapista</p>
                </div>

                <div class="flex space-x-6">
                    <a href="#" class="text-gray-400 hover:text-amber-400 transition">
                        <i class="fab fa-facebook-f text-xl"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-amber-400 transition">
                        <i class="fab fa-instagram text-xl"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-amber-400 transition">
                        <i class="fab fa-linkedin-in text-xl"></i>
                    </a>
                </div>
            </div>

            <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-400 text-sm">
                <p>© 2025 Silvia Concetta Sapienza - P.IVA 12345678901 - Tutti i diritti riservati</p>
                <p class="mt-2">Design e sviluppo by YourWebAgency</p>
            </div>
        </div>
    </footer>

    <!-- Back to top button -->
    <button id="back-to-top" class="fixed bottom-6 right-6 w-12 h-12 rounded-full bg-amber-500 text-white shadow-lg flex items-center justify-center transition opacity-0 invisible">
        <i class="fas fa-arrow-up"></i>
    </button>

    <!-- Success modal -->
    <div id="success-modal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden">
        <div class="bg-white p-8 rounded-xl max-w-md mx-4">
            <div class="text-center">
                <div class="w-16 h-16 rounded-full bg-green-100 flex items-center justify-center mx-auto mb-4">
                    <i class="fas fa-check text-green-500 text-2xl"></i>
                </div>
                <h3 class="text-xl font-semibold text-gray-800 mb-2">Richiesta inviata con successo!</h3>
                <p class="text-gray-600 mb-6">Ti contatterò al più presto per confermare l'appuntamento.</p>
                <button id="close-modal" class="bg-amber-500 hover:bg-amber-600 text-white font-medium py-2 px-6 rounded-lg transition">
                    Chiudi
                </button>
            </div>
        </div>
    </div>

    <script>
        // Mobile menu toggle
        document.getElementById('menu-toggle').addEventListener('click', function() {
            document.getElementById('mobile-menu').classList.toggle('hidden');
        });

        // Back to top button
        window.addEventListener('scroll', function() {
            var backToTopButton = document.getElementById('back-to-top');
            if (window.pageYOffset > 300) {
                backToTopButton.classList.remove('opacity-0', 'invisible');
                backToTopButton.classList.add('opacity-100', 'visible');
            } else {
                backToTopButton.classList.remove('opacity-100', 'visible');
                backToTopButton.classList.add('opacity-0', 'invisible');
            }
        });

        document.getElementById('back-to-top').addEventListener('click', function() {
            window.scrollTo({top: 0, behavior: 'smooth'});
        });

        // Form submission
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();

            // Here you would normally send the form data to your server
            // For this example, we'll just show the success modal
            document.getElementById('success-modal').classList.remove('hidden');

            // Reset form
            this.reset();
        });

        // Close modal
        document.getElementById('close-modal').addEventListener('click', function() {
            document.getElementById('success-modal').classList.add('hidden');
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                // Close mobile menu if open
                document.getElementById('mobile-menu').classList.add('hidden');

                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
