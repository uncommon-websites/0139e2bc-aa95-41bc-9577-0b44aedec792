<script lang="ts">
    // Project images
    const heroImage = "/generated/image-luxurious-modern-living-room-with-floor--1766187835456-0.webp";
    const deskImage = "/generated/image-designer-workspace-detail-with-architect-1766187845731-2.webp";
    const glassesImage = "/generated/image-close-up-of-luxury-interior-details---sc-1766187851436-3.webp";
    const bedroomImage = "/generated/image-elegant-bedroom-interior-with-curated-ar-1766187840276-1.webp";
    const bedCornerImage = "/generated/image-modern-bedroom-corner-with-custom-millwo-1766187856382-4.webp";
    const woodDetailImage = "/generated/image-architectural-detail-of-wood-joinery-and-1766187860314-5.webp";
    const shelfDetailImage = "/generated/image-custom-built-in-shelving-with-curated-ob-1766187863475-6.webp";
    const shelfFullImage = "/generated/image-wide-view-of-custom-shelving-unit-with-n-1766187866868-7.webp";
    const livingRoomImage = "/generated/image-sophisticated-living-room-with-contempor-1766187869757-8.webp";
    const hallwayImage = "/generated/image-elegant-hallway-with-architectural-light-1766187873036-9.webp";
    const kitchenImage = "/generated/image-modern-kitchen-detail-with-natural-stone-1766187877968-10.webp";
    const terraceImage = "/generated/image-outdoor-terrace-with-los-angeles-views-c-1766187883389-11.webp";
    const woodJoineryImage = "/generated/image-detail-of-custom-wood-cabinetry-and-arch-1766187888623-12.webp";
    const kitchenIslandImage = "/generated/image-modern-kitchen-island-with-natural-stone-1766187892957-13.webp";
    const ctaLeft = "/generated/image-sophisticated-home-office-with-architect-1766187897179-14.webp";
    const ctaRight = "/generated/image-elegant-dining-area-with-statement-light-1766187901314-15.webp";

</script>

<div class="w-full">
    <!-- Hero Section -->
    <section class="w-full mb-16 md:mb-24 px-4 md:px-6 max-w-[1600px] mx-auto">
        <div class="relative w-full aspect-[16/9] md:aspect-[21/9] overflow-hidden">
            <img src={heroImage} alt="Villa Montalcino" class="w-full h-full object-cover" />
            <button class="absolute bottom-6 right-6 bg-transparent border border-white/50 text-white px-4 py-2 text-xs uppercase tracking-widest hover:bg-white hover:text-black transition-colors flex items-center gap-2">
                Share
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 3.75v4.5m0-4.5h4.5m-4.5 0L9 9M3.75 20.25v-4.5m0 4.5h4.5m-4.5 0L9 15M20.25 3.75h-4.5m4.5 0v4.5m0-4.5L15 9m5.25 11.25h-4.5m4.5 0v-4.5m0 4.5L15 15" />
                </svg>
            </button>
        </div>
    </section>

    <!-- Project Info -->
    <section class="max-w-[1200px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12 md:gap-24">
            <div>
                <h1 class="font-display text-4xl md:text-5xl text-gray-900 mb-8">Villa Montalcino</h1>
                <div class="text-gray-600 text-sm leading-relaxed space-y-4 max-w-md font-light">
                    <p>
                        Nestled in the hills of Pacific Palisades with sweeping views of the Pacific Ocean, Villa Montalcino represents a harmonious dialogue between architecture, landscape, and interior design.
                    </p>
                    <p>
                        The residence, designed by Nila Interiors, merges timeless European sensibility with the relaxed elegance of California living, creating spaces that are both sculptural and deeply livable.
                    </p>
                </div>
            </div>
            <div class="grid grid-cols-2 gap-y-6 text-[11px] uppercase tracking-wider">
                <div class="text-gray-400">Private residence</div>
                <div class="text-gray-900">Pacific Palisades, CA</div>

                <div class="text-gray-400">Interior Design</div>
                <div class="text-gray-900">Nila Interiors</div>

                <div class="text-gray-400">Principal Designer</div>
                <div class="text-gray-900">Nila Tavan</div>

                <div class="col-span-2 pt-6 border-t border-gray-100 mt-2">
                    <div class="text-gray-400 mb-1">Design Approach</div>
                    <div class="text-gray-900">Architecture-Informed Interiors, Curated Material Palette, Timeless Composition</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Image Grid 1 -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-12 gap-6 items-start">
            <div class="md:col-span-5 md:col-start-2">
                <img src={deskImage} alt="Design detail" class="w-full aspect-[3/4] object-cover mb-4" />
                <p class="text-xs text-gray-400 font-light max-w-xs mt-8 leading-relaxed">
                    The residence was conceived as a sanctuary that honors both the architectural bones of the structure and the lifestyle of its inhabitants, with each space carefully curated to balance visual impact with everyday functionality.
                </p>
            </div>
            <div class="md:col-span-5 md:col-start-8 md:mt-32">
                 <img src={glassesImage} alt="Glasses detail" class="w-full aspect-square object-cover" />
            </div>
        </div>
    </section>

    <!-- Full Width Image -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <img src={bedroomImage} alt="Bedroom view" class="w-full aspect-[16/9] md:aspect-[21/9] object-cover" />
    </section>

    <!-- Image Grid 2 -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div>
                <img src={bedCornerImage} alt="Bedroom corner" class="w-full aspect-[3/4] object-cover" />
            </div>
            <div class="flex flex-col justify-between">
                <img src={woodDetailImage} alt="Material detail" class="w-full aspect-[3/4] object-cover mb-8" />
                <div class="max-w-xs ml-auto">
                     <p class="text-xs text-gray-400 font-light leading-relaxed">
                        Natural materials play a central role in the design narrative. Custom millwork, stone surfaces, and carefully selected textiles create a layered sensory experience. Each material was chosen not only for its aesthetic contribution but for its ability to age gracefully and respond to the California light.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Image Grid 3 -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-12 gap-6 items-end">
             <div class="md:col-span-5">
                <img src={shelfDetailImage} alt="Shelf detail" class="w-full aspect-[4/5] object-cover" />
            </div>
            <div class="md:col-span-7">
                <img src={shelfFullImage} alt="Shelf full view" class="w-full aspect-[4/3] object-cover" />
            </div>
        </div>
    </section>

    <!-- Large Living Room Image -->
    <section class="w-full mb-24 md:mb-32">
        <img src={livingRoomImage} alt="Living room" class="w-full h-[80vh] object-cover" />
    </section>

    <!-- Image Grid 4 & Text -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-16 items-start">
            <img src={hallwayImage} alt="Hallway" class="w-full aspect-[3/4] object-cover" />
            <div class="md:pt-32">
                 <img src={kitchenImage} alt="Kitchen detail" class="w-full aspect-[3/4] object-cover" />
            </div>
        </div>
        <div class="flex justify-end">
             <p class="text-xs text-gray-400 font-light max-w-md leading-relaxed">
                The material palette creates a multi-sensory experience that extends beyond the purely visual. Every surface, texture, and finish was selected to support a sense of calm refinement. The interplay of warm woods, natural stone, and carefully chosen textiles creates depth and character while maintaining the timeless quality that defines Nila Interiors' approach.
            </p>
        </div>
    </section>

    <!-- Terrace Image -->
    <section class="w-full mb-24 md:mb-32">
        <img src={terraceImage} alt="Terrace" class="w-full h-[70vh] object-cover" />
    </section>

    <!-- Bottom Text -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="max-w-md">
            <p class="text-xs text-gray-400 font-light leading-relaxed">
                Through meticulous attention to material sourcing and spatial composition, Villa Montalcino demonstrates Nila Interiors' commitment to creating environments that transcend trends. The result is a residence where architectural integrity, aesthetic refinement, and everyday livability converge—a space that honors both its location and the lives lived within it.
            </p>
        </div>
    </section>

    <!-- Final Grid -->
    <section class="max-w-[1600px] mx-auto px-6 mb-32 md:mb-40">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <img src={woodJoineryImage} alt="Wood joinery" class="w-full aspect-[3/4] object-cover" />
            <div class="pt-20">
                <img src={kitchenIslandImage} alt="Kitchen island" class="w-full aspect-[3/4] object-cover" />
            </div>
        </div>
    </section>

    <!-- Share Section -->
    <section class="max-w-[1600px] mx-auto px-6 mb-32">
        <h3 class="font-display text-2xl mb-6">Share</h3>
        <div class="flex gap-6 text-xs text-gray-400 uppercase tracking-wide">
            <a href="#" class="hover:text-black transition-colors">Pinterest</a>
            <a href="#" class="hover:text-black transition-colors">Twitter</a>
            <a href="#" class="hover:text-black transition-colors">E-mail</a>
            <a href="#" class="hover:text-black transition-colors">LinkedIn</a>
            <a href="#" class="hover:text-black transition-colors">Facebook</a>
        </div>
    </section>

    <!-- Bottom CTA -->
    <section class="w-full grid grid-cols-1 md:grid-cols-2 h-[600px]">
        <div class="relative group overflow-hidden">
            <img src={ctaLeft} alt="View Portfolio" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" />
            <div class="absolute inset-0 bg-black/20 group-hover:bg-black/30 transition-colors"></div>
            <div class="absolute inset-0 flex flex-col items-center justify-center text-white text-center p-6">
                <h2 class="font-display text-3xl md:text-4xl mb-2">View Portfolio</h2>
                <p class="text-sm font-light mb-8 opacity-90">Explore our curated collection of residential projects.</p>
                <button class="border border-white px-8 py-3 text-xs uppercase tracking-widest hover:bg-white hover:text-black transition-colors">
                    See Projects
                </button>
            </div>
        </div>
        <div class="relative group overflow-hidden">
            <img src={ctaRight} alt="Start a Project" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" />
            <div class="absolute inset-0 bg-black/20 group-hover:bg-black/30 transition-colors"></div>
            <div class="absolute inset-0 flex flex-col items-center justify-center text-white text-center p-6">
                <h2 class="font-display text-3xl md:text-4xl mb-2">Start a Project</h2>
                <p class="text-sm font-light mb-8 opacity-90">Let's create something timeless together.</p>
                <button class="border border-white px-8 py-3 text-xs uppercase tracking-widest hover:bg-white hover:text-black transition-colors">
                    Get in Touch
                </button>
            </div>
        </div>
    </section>
</div>

