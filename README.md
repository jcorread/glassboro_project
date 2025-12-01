<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glassboro Wildlife Management Area</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&family=Merriweather:wght@300;400;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['DM Sans', 'sans-serif'],
                        serif: ['Merriweather', 'serif'],
                    },
                    colors: {
                        forest: {
                            800: '#1b4332',
                            900: '#081c15',
                        },
                        sage: {
                            100: '#e8f5e9',
                            200: '#c8e6c9',
                        },
                        earth: {
                            500: '#d08c60',
                            600: '#a66e4a',
                        },
                        cream: '#fdfbf7',
                    }
                }
            }
        }
    </script>
    <style>
        .hero-bg {
            background-image: linear-gradient(rgba(8, 28, 21, 0.6), rgba(8, 28, 21, 0.7)), url('https://www.alltrails.com/mugen/image/location-app-router?url=https%3A%2F%2Fimages.alltrails.com%2FeyJidWNrZXQiOiJhc3NldHMuYWxsdHJhaWxzLmNvbSIsImtleSI6InVwbG9hZHMvcGhvdG8vaW1hZ2UvNjI5MjEzNjIvMjAxNWUzNTQ5ZDlhNjY0N2Y1ODNlZjdjYzE3MWQyNTUuanBnIiwiZWRpdHMiOnsidG9Gb3JtYXQiOiJ3ZWJwIiwicmVzaXplIjp7IndpZHRoIjoxMDgwLCJoZWlnaHQiOjcwMCwiZml0IjoiY292ZXIifSwicm90YXRlIjpudWxsLCJqcGVnIjp7InRyZWxsaXNRdWFudGlzYXRpb24iOnRydWUsIm92ZXJzaG9vdERlcmluZ2luZyI6dHJ1ZSwib3B0aW1pc2VTY2FucyI6dHJ1ZSwicXVhbnRpc2F0aW9uVGFibGUiOjN9fX0%3D&w=3840&q=90');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }
        .pattern-bg {
            background-color: #fdfbf7;
            background-image: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%231b4332' fill-opacity='0.05'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
        }
    </style>
</head>
<body class="font-sans text-gray-800 bg-cream antialiased">

    <!-- Navigation -->
    <nav class="fixed w-full z-50 bg-forest-900/95 backdrop-blur-sm text-white border-b border-forest-800 transition-all duration-300" id="navbar">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <div class="flex items-center">
                    <i class="fa-solid fa-tree text-earth-500 mr-2 text-xl"></i>
                    <span class="font-serif font-bold text-lg tracking-wide">Glassboro WMA</span>
                </div>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-8">
                        <a href="#about" class="hover:text-earth-500 transition-colors px-3 py-2 rounded-md text-sm font-medium">About</a>
                        <a href="#habitats" class="hover:text-earth-500 transition-colors px-3 py-2 rounded-md text-sm font-medium">Ecosystem</a>
                        <a href="#species" class="hover:text-earth-500 transition-colors px-3 py-2 rounded-md text-sm font-medium">Species</a>
                        <a href="#controversy" class="hover:text-earth-500 transition-colors px-3 py-2 rounded-md text-sm font-medium">The 2023 Incident</a>
                        <a href="#recreation" class="bg-earth-500 hover:bg-earth-600 text-white px-4 py-2 rounded-md text-sm font-medium transition-colors">Visit Guide</a>
                    </div>
                </div>
                <!-- Mobile menu button -->
                <div class="md:hidden">
                    <button onclick="document.getElementById('mobile-menu').classList.toggle('hidden')" class="text-gray-300 hover:text-white p-2">
                        <i class="fa-solid fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div class="hidden md:hidden bg-forest-900 border-t border-forest-800" id="mobile-menu">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#about" class="block hover:text-earth-500 px-3 py-2 rounded-md text-base font-medium">About</a>
                <a href="#habitats" class="block hover:text-earth-500 px-3 py-2 rounded-md text-base font-medium">Ecosystem</a>
                <a href="#species" class="block hover:text-earth-500 px-3 py-2 rounded-md text-base font-medium">Species</a>
                <a href="#controversy" class="block hover:text-earth-500 px-3 py-2 rounded-md text-base font-medium">Controversy</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="relative h-screen flex items-center justify-center hero-bg text-center px-4">
        <div class="max-w-4xl mx-auto transform translate-y-[-10%]">
            <div class="inline-block mb-4 px-4 py-1 border border-earth-500 text-earth-500 rounded-full text-sm font-bold uppercase tracking-widest bg-forest-900/50 backdrop-blur-sm">
                Gloucester County, New Jersey
            </div>
            <h1 class="font-serif text-5xl md:text-7xl font-bold text-white mb-6 leading-tight drop-shadow-lg">
                Glassboro Wildlife <br> <span class="text-earth-500">Management Area</span>
            </h1>
            <p class="text-xl md:text-2xl text-gray-200 font-light max-w-2xl mx-auto mb-10 leading-relaxed">
                An ecological assessment of 2,393 acres of protected biological reserve, acting as a critical ecotone between the Delaware Valley and the Pine Barrens.
            </p>
            <a href="#about" class="inline-flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-forest-900 bg-white hover:bg-gray-100 md:py-4 md:text-lg md:px-10 transition-all shadow-lg">
                Explore the WMA
                <i class="fa-solid fa-arrow-down ml-2"></i>
            </a>
        </div>
    </header>

    <!-- Overview / Vital Stats -->
    <section id="about" class="py-20 pattern-bg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="font-serif text-3xl md:text-4xl font-bold text-forest-900 mb-4">Geographic Context</h2>
                <div class="w-24 h-1 bg-earth-500 mx-auto rounded"></div>
                <p class="mt-4 text-xl text-gray-600 max-w-3xl mx-auto">
                    Managed by the NJ Department of Environmental Protection, this area serves as a vital aquifer recharge zone and a regional biodiversity node.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Stat Card 1 -->
                <div class="bg-white rounded-xl shadow-xl p-8 border-t-4 border-forest-800 hover:-translate-y-1 transition-transform duration-300">
                    <div class="flex items-center justify-between mb-4">
                        <div class="p-3 bg-sage-100 rounded-lg">
                            <i class="fa-solid fa-ruler-combined text-forest-800 text-2xl"></i>
                        </div>
                        <span class="text-4xl font-serif font-bold text-forest-900">2,393</span>
                    </div>
                    <h3 class="text-lg font-bold text-gray-700 uppercase tracking-wide">Total Acres</h3>
                    <p class="text-gray-500 mt-2">A massive contiguous tract of land spanning Glassboro, Clayton, and Monroe Township.</p>
                </div>

                <!-- Stat Card 2 -->
                <div class="bg-white rounded-xl shadow-xl p-8 border-t-4 border-earth-500 hover:-translate-y-1 transition-transform duration-300">
                    <div class="flex items-center justify-between mb-4">
                        <div class="p-3 bg-orange-50 rounded-lg">
                            <i class="fa-solid fa-map-location-dot text-earth-500 text-2xl"></i>
                        </div>
                        <span class="text-4xl font-serif font-bold text-forest-900">#15</span>
                    </div>
                    <h3 class="text-lg font-bold text-gray-700 uppercase tracking-wide">Deer Management Zone</h3>
                    <p class="text-gray-500 mt-2">Designated specifically for wildlife conservation and regulated hunting activities.</p>
                </div>

                <!-- Stat Card 3 -->
                <div class="bg-white rounded-xl shadow-xl p-8 border-t-4 border-forest-800 hover:-translate-y-1 transition-transform duration-300">
                    <div class="flex items-center justify-between mb-4">
                        <div class="p-3 bg-sage-100 rounded-lg">
                            <i class="fa-solid fa-leaf text-forest-800 text-2xl"></i>
                        </div>
                        <span class="text-3xl font-serif font-bold text-forest-900">Ecotone</span>
                    </div>
                    <h3 class="text-lg font-bold text-gray-700 uppercase tracking-wide">Ecological Type</h3>
                    <p class="text-gray-500 mt-2">A transition zone mixing fertile Delaware Valley soils with acidic Pine Barrens sands.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Habitats Grid -->
    <section id="habitats" class="py-20 bg-forest-900 text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row justify-between items-end mb-12">
                <div class="max-w-2xl">
                    <h2 class="font-serif text-3xl md:text-4xl font-bold mb-4">A Mosaic of Habitats</h2>
                    <p class="text-sage-200 text-lg">The diversity of the land supports complex fungal networks, seed banks, and varied wildlife.</p>
                </div>
                <div class="hidden md:block">
                    <a href="https://dep.nj.gov/njfw/wildlife/wildlife-management-areas/" target="_blank" class="text-earth-500 hover:text-earth-400 font-bold decoration-2 underline-offset-4 hover:underline">View Official Maps <i class="fa-solid fa-arrow-right ml-1"></i></a>
                </div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <!-- Tile 1 -->
                <div class="group relative overflow-hidden rounded-lg h-80">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTDupy81SbPNVZPvgjrm-BoOq8__Ayb-Ve62Q&s" alt="Forest" class="w-full h-full object-cover transform group-hover:scale-110 transition-duration-500 transition-transform duration-700">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent flex flex-col justify-end p-6">
                        <h3 class="font-serif text-xl font-bold text-white mb-1">Contiguous Forests</h3>
                        <p class="text-sm text-gray-300">Mature oak and maple stands providing deep cover.</p>
                    </div>
                </div>
                <!-- Tile 2 -->
                <div class="group relative overflow-hidden rounded-lg h-80">
                    <img src="https://scontent-atl3-3.xx.fbcdn.net/v/t39.30808-6/494346304_1129671412508609_1245057519750166507_n.jpg?stp=dst-jpg_s590x590_tt6&_nc_cat=109&ccb=1-7&_nc_sid=127cfc&_nc_ohc=czOw0ypBXfcQ7kNvwFACGBP&_nc_oc=AdmYU5yJu60Tv8VU5SO5cGzjAQeVpQvVbIs1QjhQcOSp0dF5QA3hu_IOhbIZc7Z3XDA&_nc_zt=23&_nc_ht=scontent-atl3-3.xx&_nc_gid=yG_ydDevnTUK9gmOJinvQQ&oh=00_Afj5L4HBy9qBiC8bKlbPSjNr8poupJmh_4IX0Zx44j6gyw&oe=6932B55F" alt="Swamp" class="w-full h-full object-cover transform group-hover:scale-110 transition-duration-500 transition-transform duration-700">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent flex flex-col justify-end p-6">
                        <h3 class="font-serif text-xl font-bold text-white mb-1">Cedar Swamps</h3>
                        <p class="text-sm text-gray-300">Acidic wetlands home to specialized orchids.</p>
                    </div>
                </div>
                <!-- Tile 3 -->
                <div class="group relative overflow-hidden rounded-lg h-80">
                    <img src="https://southjerseyhiking.wordpress.com/wp-content/uploads/2014/05/cropped-dscn06442.jpg" alt="Upland Field" class="w-full h-full object-cover transform group-hover:scale-110 transition-duration-500 transition-transform duration-700">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent flex flex-col justify-end p-6">
                        <h3 class="font-serif text-xl font-bold text-white mb-1">Pine-Oak Uplands</h3>
                        <p class="text-sm text-gray-300">Sandy soils supporting fossorial reptiles.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Biodiversity Showcase -->
    <section id="species" class="py-20 pattern-bg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="font-serif text-3xl md:text-4xl font-bold text-center text-forest-900 mb-16">Biodiversity Highlights</h2>
            
            <!-- Feature 1: The Owl -->
            <div class="flex flex-col lg:flex-row items-center gap-12 mb-20">
                <div class="lg:w-1/2">
                    <div class="relative rounded-2xl overflow-hidden shadow-2xl rotate-1 hover:rotate-0 transition-transform duration-500 border-8 border-white">
                        <img src="https://static01.nyt.com/images/2023/04/14/multimedia/14nj-birdflub-zmcl/14nj-birdflub-zmcl-mediumSquareAt3X.jpg" alt="Barred Owl" class="w-full h-auto">
                        <div class="absolute bottom-4 right-4 bg-black/60 text-white px-3 py-1 rounded text-xs backdrop-blur-sm">Strix varia</div>
                    </div>
                </div>
                <div class="lg:w-1/2">
                    <span class="text-earth-500 font-bold tracking-widest uppercase text-sm mb-2 block">Raptor of the Canopy</span>
                    <h3 class="font-serif text-3xl font-bold text-forest-900 mb-4">The Barred Owl</h3>
                    <div class="flex items-center mb-6">
                        <span class="bg-orange-100 text-orange-800 text-xs font-semibold px-2.5 py-0.5 rounded border border-orange-400">NJ Threatened</span>
                    </div>
                    <p class="text-lg text-gray-600 mb-6 leading-relaxed">
                        An indicator species of old-growth wetland health. Listed as <strong>Threatened</strong> in New Jersey, these owls require large tracts of contiguous swamp forest with mature cavity trees for nesting. They share the woods with Red-shouldered Hawks, an endangered raptor sensitive to habitat fragmentation.
                    </p>
                    <div class="p-4 bg-white border-l-4 border-forest-800 shadow-sm rounded-r-lg">
                        <p class="text-sm text-gray-800 italic font-serif">"We have to stop pitting one species against another. It makes no sense to destroy a mature wetland forest to create habitat for a common game bird."</p>
                        <p class="text-xs text-earth-600 font-bold mt-2 uppercase tracking-wide">— Emile DeVito, Ph.D., NJ Conservation Foundation</p>
                    </div>
                </div>
            </div>

            <!-- Feature 2: The Warbler (Reversed) -->
            <div class="flex flex-col lg:flex-row-reverse items-center gap-12">
                <div class="lg:w-1/2">
                    <div class="relative rounded-2xl overflow-hidden shadow-2xl -rotate-1 hover:rotate-0 transition-transform duration-500 border-8 border-white">
                        <img src="https://www.allaboutbirds.org/guide/assets/og/75713971-1200px.jpg" alt="Yellow Warbler (representing Prothonotary)" class="w-full h-auto">
                        <div class="absolute bottom-4 right-4 bg-black/60 text-white px-3 py-1 rounded text-xs backdrop-blur-sm">Protonotaria citrea</div>
                    </div>
                </div>
                <div class="lg:w-1/2">
                    <span class="text-earth-500 font-bold tracking-widest uppercase text-sm mb-2 block">Avian Hotspot</span>
                    <h3 class="font-serif text-3xl font-bold text-forest-900 mb-4">The "Swamp Warblers"</h3>
                    <p class="text-lg text-gray-600 mb-6 leading-relaxed">
                        Glassboro is a key destination for neotropical migrants. The wet woods along Lincoln and Carpenter Avenues are famous for breeding <strong>Prothonotary Warblers</strong> (known as "golden swamp warblers"), Hooded Warblers, and Kentucky Warblers.
                    </p>
                    <ul class="space-y-3">
                        <li class="flex items-start">
                            <i class="fa-solid fa-check text-forest-800 mt-1 mr-3"></i>
                            <span class="text-gray-600">Dependent on standing dead trees (snags).</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa-solid fa-check text-forest-800 mt-1 mr-3"></i>
                            <span class="text-gray-600">Requires dense understory for protection.</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa-solid fa-check text-forest-800 mt-1 mr-3"></i>
                            <span class="text-gray-600">Top inland location for spring migration.</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- The 2023 Incident -->
    <section id="controversy" class="py-20 bg-stone-100 border-y border-stone-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-white rounded-2xl shadow-xl overflow-hidden">
                <div class="bg-red-700 px-8 py-4">
                    <h2 class="text-white font-serif font-bold text-xl flex items-center">
                        <i class="fa-solid fa-triangle-exclamation mr-3"></i>
                        The 2023 Habitat Incident
                    </h2>
                </div>
                <div class="p-8 md:p-12 grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                    <div>
                        <img src="https://www.njspotlightnews.org/wp-content/uploads/sites/123/2023/03/IMG_1856-WMA-7-900x506.jpg" alt="Cleared forest at Glassboro WMA" class="w-full h-auto rounded-xl shadow-md border-4 border-stone-200">
                        <p class="text-sm text-gray-500 mt-2 italic text-center">Photo shows the aftermath of the clearing of mature wetland forest.</p>
                    </div>
                    <div>
                        <h3 class="text-2xl font-bold text-gray-900 mb-4">Ecological Conflict: Game Management vs. Preservation</h3>
                        <p class="text-gray-600 text-lg mb-8">
                            In February 2023, a significant controversy erupted when the Division of Fish & Wildlife cleared approximately <strong>21 acres of mature wetland forest</strong>. The goal was to create "early successional habitat" for the American Woodcock, a game bird.
                        </p>
                        
                        <div class="grid grid-cols-1 gap-6">
                            <div class="bg-red-50 p-6 rounded-lg border border-red-100 shadow-sm">
                                <h4 class="font-bold text-red-900 mb-2 flex items-center"><i class="fa-solid fa-xmark mr-2"></i> The Action</h4>
                                <p class="text-sm text-red-800">
                                    Clear-cutting and bulldozing of stumps destroyed ancient soil horizons and removed the canopy required by endangered raptors.
                                </p>
                            </div>
                            <div class="bg-red-50 p-6 rounded-lg border border-red-100 shadow-sm">
                                <h4 class="font-bold text-red-900 mb-2 flex items-center"><i class="fa-solid fa-gavel mr-2"></i> The Consequence</h4>
                                <p class="text-sm text-red-800">
                                    The NJDEP issued a <strong>Notice of Violation</strong> against its own division for violating freshwater wetland protections. The event galvanized conservationists.
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Recreation Grid -->
    <section id="recreation" class="py-20 pattern-bg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="font-serif text-3xl md:text-4xl font-bold text-forest-900 mb-4">Multi-Use Recreation</h2>
            <p class="text-gray-600 max-w-2xl mx-auto mb-16">The WMA is public land, but users must be aware of conflicting activities—specifically hunting and hiking.</p>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Card 1 -->
                <div class="bg-white p-8 rounded-xl shadow-lg border-b-4 border-earth-500 group hover:shadow-2xl transition-all">
                    <div class="w-16 h-16 bg-earth-100 text-earth-600 rounded-full flex items-center justify-center mx-auto mb-6 group-hover:bg-earth-500 group-hover:text-white transition-colors">
                        <i class="fa-solid fa-person-rifle text-2xl"></i>
                    </div>
                    <h3 class="font-serif text-xl font-bold text-gray-900 mb-2">Hunting</h3>
                    <p class="text-gray-500 text-sm">The primary management goal. Famous for Pheasant stocking (Nov-Dec) and deer hunting (Bow/Shotgun).</p>
                </div>

                <!-- Card 2 -->
                <div class="bg-white p-8 rounded-xl shadow-lg border-b-4 border-forest-800 group hover:shadow-2xl transition-all">
                    <div class="w-16 h-16 bg-green-100 text-forest-800 rounded-full flex items-center justify-center mx-auto mb-6 group-hover:bg-forest-800 group-hover:text-white transition-colors">
                        <i class="fa-solid fa-binoculars text-2xl"></i>
                    </div>
                    <h3 class="font-serif text-xl font-bold text-gray-900 mb-2">Birding</h3>
                    <p class="text-gray-500 text-sm">A "Must-Visit" eBird hotspot. Best viewing is along the wet woods of Lincoln and Carpenter Avenues.</p>
                </div>

                <!-- Card 3 -->
                <div class="bg-white p-8 rounded-xl shadow-lg border-b-4 border-yellow-500 group hover:shadow-2xl transition-all">
                    <div class="w-16 h-16 bg-yellow-100 text-yellow-600 rounded-full flex items-center justify-center mx-auto mb-6 group-hover:bg-yellow-500 group-hover:text-white transition-colors">
                        <i class="fa-solid fa-person-hiking text-2xl"></i>
                    </div>
                    <h3 class="font-serif text-xl font-bold text-gray-900 mb-2">Hiking Safety</h3>
                    <p class="text-gray-500 text-sm">Trails are sand roads/firebreaks. <strong>Blaze Orange</strong> is mandatory during hunting seasons.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Species Status Table -->
    <section class="py-20 bg-forest-900 text-white">
        <div class="max-w-4xl mx-auto px-4">
            <h2 class="font-serif text-2xl md:text-3xl font-bold mb-8 text-center">Conservation Status Report (2025)</h2>
            <div class="overflow-x-auto bg-forest-800 rounded-lg shadow-xl border border-forest-700">
                <table class="w-full text-left border-collapse">
                    <thead>
                        <tr class="bg-forest-900 border-b border-forest-700 text-earth-500 text-sm uppercase tracking-wider">
                            <th class="p-4 font-semibold">Species</th>
                            <th class="p-4 font-semibold">Type</th>
                            <th class="p-4 font-semibold">NJ Status</th>
                            <th class="p-4 font-semibold">Habitat Need</th>
                        </tr>
                    </thead>
                    <tbody class="divide-y divide-forest-700 text-sm text-gray-300">
                        <tr class="hover:bg-forest-700/50 transition-colors">
                            <td class="p-4 font-medium text-white">Barred Owl</td>
                            <td class="p-4">Bird (Raptor)</td>
                            <td class="p-4"><span class="bg-orange-900 text-orange-200 px-2 py-1 rounded text-xs border border-orange-700">Threatened</span></td>
                            <td class="p-4">Mature Wetland Forest</td>
                        </tr>
                        <tr class="hover:bg-forest-700/50 transition-colors">
                            <td class="p-4 font-medium text-white">Red-shouldered Hawk</td>
                            <td class="p-4">Bird (Raptor)</td>
                            <td class="p-4"><span class="bg-red-900 text-red-200 px-2 py-1 rounded text-xs border border-red-700">Endangered</span></td>
                            <td class="p-4">Riparian Forest</td>
                        </tr>
                        <tr class="hover:bg-forest-700/50 transition-colors">
                            <td class="p-4 font-medium text-white">Pine Barrens Treefrog</td>
                            <td class="p-4">Amphibian</td>
                            <td class="p-4"><span class="bg-orange-900 text-orange-200 px-2 py-1 rounded text-xs border border-orange-700">Threatened</span></td>
                            <td class="p-4">Acidic Vernal Pools</td>
                        </tr>
                        <tr class="hover:bg-forest-700/50 transition-colors">
                            <td class="p-4 font-medium text-white">Northern Pine Snake</td>
                            <td class="p-4">Reptile</td>
                            <td class="p-4"><span class="bg-orange-900 text-orange-200 px-2 py-1 rounded text-xs border border-orange-700">Threatened</span></td>
                            <td class="p-4">Sandy Uplands</td>
                        </tr>
                        <tr class="hover:bg-forest-700/50 transition-colors">
                            <td class="p-4 font-medium text-white">American Woodcock</td>
                            <td class="p-4">Bird (Game)</td>
                            <td class="p-4"><span class="bg-yellow-900 text-yellow-200 px-2 py-1 rounded text-xs border border-yellow-700">Special Concern</span></td>
                            <td class="p-4">Young Forest / Fields</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-forest-950 text-gray-400 py-12 border-t border-forest-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 md:grid-cols-3 gap-8 text-sm">
            <div>
                <h4 class="text-white font-bold mb-4 font-serif">Glassboro WMA</h4>
                <p>A delicate balance of conservation and recreation. Future stewardship depends on protecting contiguous habitats.</p>
            </div>
            <div>
                <h4 class="text-white font-bold mb-4 font-serif">Sources</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-earth-500">NJ Division of Fish & Wildlife</a></li>
                    <li><a href="#" class="hover:text-earth-500">Pinelands Alliance Report</a></li>
                    <li><a href="#" class="hover:text-earth-500">eBird Hotspot Data</a></li>
                    <li><a href="https://www.iucnredlist.org" target="_blank" class="hover:text-earth-500">IUCN Red List</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-bold mb-4 font-serif">Visit</h4>
                <p class="mb-2"><i class="fa-solid fa-location-dot mr-2"></i> Fries Mill Road & Carpenter Ave</p>
                <p><i class="fa-solid fa-map mr-2"></i> Gloucester County, NJ</p>
                
                <div class="mt-6 pt-6 border-t border-forest-800">
                    <h5 class="text-white font-bold mb-2 font-serif">Project Team</h5>
                    <p class="text-earth-500 font-medium">Diana Espinoza-Cruz</p>
                    <p class="text-earth-500 font-medium">Jose D Correa Diaz</p>
                    <p class="mt-2 text-xs text-gray-600">Ecology Final Project</p>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Simple script to handle sticky navbar background opacity on scroll
        window.addEventListener('scroll', function() {
            const navbar = document.getElementById('navbar');
            if (window.scrollY > 50) {
                navbar.classList.add('shadow-lg');
            } else {
                navbar.classList.remove('shadow-lg');
            }
        });
    </script>
</body>
</html>
