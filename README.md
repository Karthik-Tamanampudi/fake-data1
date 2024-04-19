const starDatabase = [
    {
      id: 1,
      type: "Main Sequence Stars",
      description: "A normal star forms from a clump of dust and gas in a stellar nursery. Over hundreds of thousands of years, the clump gains mass, starts to spin, and heats up. When the clump's core heats up to millions of degrees, nuclear fusion starts. This process occurs when two protons, the nuclei of hydrogen atoms, merge to form one helium nucleus. Fusion releases energy that heats the star, creating pressure that pushes against the force of its gravity. A star is born. Scientists call a star that is fusing hydrogen to helium in its core a main sequence star. Main sequence stars make up around 90% of the universe’s stellar population. They range in luminosity, color, and size – from a tenth to 200 times the Sun’s mass – and live for millions to billions of years.",
      image: "images/main sequence star.jpeg"
    },
    {
      id: 2,
      type: "Red Giants",
      description: "When a main sequence star less than eight times the Sun’s mass runs out of hydrogen in its core, it starts to collapse because the energy produced by fusion is the only force fighting gravity’s tendency to pull matter together. But squeezing the core also increases its temperature and pressure, so much so that its helium starts to fuse into carbon, which also releases energy. Hydrogen fusion begins moving into the star’s outer layers, causing them to expand. The result is a red giant, which would appear more orange than red. Eventually, the red giant becomes unstable and begins pulsating, periodically expanding and ejecting some of its atmosphere. Eventually, all of its outer layers blow away, creating an expanding cloud of dust and gas called a planetary nebula. The Sun will become a red giant in about 5 billion years.",
      image: "images/red giant.jpeg"
    },
    {
        id: 3,
        type: "White Dwarf",
        description: "After a red giant has shed all its atmosphere, only the core remains. Scientists call this kind of stellar remnant a white dwarf. A white dwarf is usually Earth-size but hundreds of thousands of times more massive. A teaspoon of its material would weigh more than a pickup truck. A white dwarf produces no new heat of its own, so it gradually cools over billions of years. Despite the name, white dwarfs can emit visible light that ranges from blue white to red. Scientists sometimes find that white dwarfs are surrounded by dusty disks of material, debris, and even planets – leftovers from the original star’s red giant phase. In about 10 billion years, after its time as a red giant, the Sun will become a white dwarf.",
        image: "images/white dwarf.jpeg"
    },
    {
        id: 4,
        type: "Neutron Stars",
        description: "A neutron star forms when a main sequence star with between about eight and 20 times the Sun’s mass runs out of hydrogen in its core. (Heavier stars produce stellar-mass black holes.) The star starts fusing helium to carbon, like lower-mass stars. But then, when the core runs out of helium, it shrinks, heats up, and starts converting its carbon into neon, which releases energy. This process continues as the star converts neon into oxygen, oxygen into silicon, and finally silicon into iron. These processes produce energy that keep the core from collapsing, but each new fuel buys it less and less time. By the time silicon fuses into iron, the star runs out of fuel in a matter of days. The next step would be fusing iron into some heavier element, but doing so requires energy instead of releasing it. The core collapses and then rebounds back to its original size, creating a shock wave that travels through the star’s outer layers. The result is a huge explosion called a supernova. The remnant core is a superdense neutron star.",
        image: "images/neutron star.jpeg"
    },
    {
        id: 5,
        type: "Red Dwarf",
        description: "Red dwarfs are the smallest main sequence stars – just a fraction of the Sun’s size and mass. They’re also the coolest, and appear more orange in color than red. When a red dwarf produces helium via fusion in its core, the released energy brings material to the star’s surface, where it cools and sinks back down, taking along a fresh supply of hydrogen to the core. Because of this constant churning, red dwarfs can steadily burn through their entire supply of hydrogen over trillions of years without changing their internal structures, unlike other stars. Scientists think some low-mass red dwarfs, those with just a third of the Sun’s mass, have life spans longer than the current age of the universe, up to about 14 trillion years. Red dwarfs are also born in much greater numbers than more massive stars. Because of that, and because they live so long, red dwarfs make up around 75% of the Milky Way galaxy’s stellar population.",
        image: "images/red dwarf star.jpeg"
    },
    {
        id: 6,
        type: "Brown Dwarf",
        description: "Brown dwarfs aren’t technically stars. They’re more massive than planets but not quite as massive as stars. Generally, they have between 13 and 80 times the mass of Jupiter. They emit almost no visible light, but scientists have seen a few in infrared light. Some brown dwarfs form the same way as main sequence stars, from gas and dust clumps in nebulae, but they never gain enough mass to do fusion on the scale of a main sequence star. Others may form like planets, from disks of gas and dust around stars.",
        image: "images/brown dwarf.jpeg"
    },
    {
        id: 7,
        type: "Protostars",
        description: "A protostar is a collection of gas that has collapsed down from a giant molecular cloud. It is what exists before a star forms. This stage usually lasts around 100,000 years and, over time, gravity and pressure increases, forcing the protostar to collapse.",
        image: "images/protostar.jpeg"
    },
   
];

const constellations = [
    {
      name: "Scorpius",
      description: "Scorpius is a zodiac constellation located in the Southern celestial hemisphere, where it sits near the center of the Milky Way, between Libra to the west and Sagittarius to the east.",
      image: "images/Scorpius.jpeg"
    },
    {
        name: "Orion",
        description: "Orion is a prominent set of stars visible during winter in the northern celestial hemisphere. It is one of the 88 modern constellations; it was among the 48 constellations listed by the 2nd-century astronomer Ptolemy. It is named for a hunter in Greek mythology",
        image: "images/Orion.jpeg"
    },
    {
        name:"Ursa Major",
        description: "Ursa Major is a constellation in the northern sky, whose associated mythology likely dates back into prehistory. Its Latin name means 'greater bear', referring to and contrasting it with nearby Ursa Minor, the lesser bear",
        image: "images/Ursa Major.jpeg"
    },
    {
        name:"Aquila",
        description: "Aquila is a constellation on the celestial equator. Its name is Latin for 'eagle' and it represents the bird that carried Zeus/Jupiter's thunderbolts in Greek-Roman mythology. Its brightest star, Altair, is one vertex of the Summer Triangle asterism",
        image: "images/Aquila.jpeg"
    },
    {
        name:"Ursa Minor",
        description: "Ursa Minor, also known as the Little Bear, is a constellation located in the far northern sky. As with the Great Bear, the tail of the Little Bear may also be seen as the handle of a ladle, hence the North American name, Little Dipper: seven stars with four in its bowl like its partner the Big Dipper.",
        image: "images/Ursa Minor.jpeg"
    },
    {
        name: "boötes",
        description: "Boötes is a constellation in the northern sky, located between 0° and +60° declination, and 13 and 16 hours of right ascension on the celestial sphere. The name comes from Latin: Boōtēs, which comes from Greek: Βοώτης, translit. Boṓtēs herdsman or plowman",
        image: "images/boötes/jpeg"
    },
    {
        name: "Lyra",
        description: "Lyra is a small constellation. It is one of the 48 listed by the 2nd century astronomer Ptolemy, and is one of the modern 88 constellations recognized by the International Astronomical Union.",
        image: "images/Lyra.jpeg"
    },
    {
        name: "Delphinus",
        description: "Delphinus is a small constellation in the Northern Celestial Hemisphere, close to the celestial equator. Its name is the Latin version for the Greek word for dolphin",
        image: "images/Delphinus.jpeg"
    },
    {
        name: "Canis Major",
        description: "Canis Major is a constellation in the southern celestial hemisphere. In the second century, it was included in Ptolemy's 48 constellations, and is counted among the 88 modern constellations.",
        image: "images/Canis Major.jpeg"
    },
    {
        name: "Cygnus",
        description: "Cygnus is a northern constellation on the plane of the Milky Way, deriving its name from the Latinized Greek word for swan. Cygnus is one of the most recognizable constellations of the northern summer and autumn, and it features a prominent asterism known as the Northern Cross.",
        image: "images/Cygnus.jpeg"
    },
    {
        name: "Aries",
        description: "Aries: Aries is one of the constellations of the zodiac. It is located in the Northern celestial hemisphere between Pisces to the west and Taurus to the east. The name Aries is Latin for ram. Its old astronomical symbol is",
        image: "images/Aries.jpeg"
    },
    {
        name: "Canes Venatici",
        description: "Canes Venatici is one of the 88 constellations designated by the International Astronomical Union. It is a small northern constellation that was created by Johannes Hevelius in the 17th century",
        image: "images/Canes Venatici.jpeg"
    }

    // ... (more constellation data)
];

const planets = [
    {
      name: "Terrestrial Planet",
      description: "A terrestrial planet is the broader classification of silicate planets as they have solid surfaces. The composition of the core of terrestrial planets is also diverse with some being made of iron while others are made of carbon-based compounds. However, there are terrestrial planets which do not have a core which is known as coreless planets.",
      image: "images/Terrestrial Planet.jpeg"
    },
    {
        name: "Silicate Planet", 
        description: "A silicate planet is primarily made up of silicate compounds. These planets are characterized by a solid crust, a silicate mantle, and an iron-based core. Depending on the presence of tectonic and volcanic activity, these planets can also have mountains, canyons, and valleys. All the four planets closest to the Sun (Mercury, Venus, Earth, and Mars) are categorized as silicate planets.",
        image: "images/silicate planet.jpeg"
      },
      {
        name: "Puffy Planet",
        description:"Puffy planets are gas giants which exist close to their stars and temperatures from the stars cause their atmospheres to expand and result in such planets having a large equatorial radius but relatively low densities. There are no such planets in the solar system, but few have been discovered beyond our solar system including WASP-12b and WASP 17b.",
        image: "images/fuffy planet.jpeg"
      },
      {
        name: "Protoplanet",
        description: "A protoplanet are large celestial bodies which were formed as a result of the collision of planetesimals and are also known are planet embryos. There are no established protoplanets in our solar system with the closest equivalent being asteroids such as Pallas and Vesta.",
        image: "images/protoplanet.jpeg"
      },
      {
        name: "Ocean Planet",
        description: "An ocean planet is a hypothetical type of planet which is thought to be wholly or predominantly covered by water. These planets have 10% of their mass being water (water accounts for only 0.05% of the Earth’s mass). Ocean planets have oceans hundreds of miles in depth.",
        image: "images/ocean planet.jpeg"
      },
      {
        name: "Lava Planet",
        description: "Lava planet is a theoretical type of planet which is characterized by the presence of molten lava covering its surface. These planets are believed to have intense volcanic activity as a result of a recent large collision event or a planet in its infancy. These planets are also believed to exist within proximity of their respective stars.",
        image: "images/lava planet.jpeg"
      },
      {
        name: "Iron Planet",
        description: "An iron planet is a type of planet which is mainly made up of its iron-rich core. Such planets are also recognized for the limited presence or complete absence of a mantle. Scientists believe that these types of planets were initially terrestrial planets but had their mantles stripped away as a result of giant impacts. Mercury is the only iron planet in our solar system.",
        image: "images/iron planet.jpeg"
      },
      {
        name: "Ice Planet",
        description: "An ice planet is is predominantly made up of volatile compounds such as water, methane, and ammonia in their frozen states. These planets experience extremely low temperatures (below negative (-) 13 degrees Celsius). Our solar system does not have any ice planets, as the only icy objects which have these characteristics are too small to be classified as planets. Ice planets are key candidates of the presence of extraterrestrial life as scientists believe these planets have sub surface oceans which have conditions suitable to accommodate life.",
        image: "images/ice planet.jpeg"
      },
      {
        name: "Ice Giant",
        description: "Ice giants are planets which are mainly composed of dense gases which are heavier than those found in gas giants. These planets which were initially categorized as gas giants were established to be distinct in composition as they are primarily made up of carbon, sulfur, oxygen, and nitrogen instead of the hydrogen and helium found in gas giants. Neptune and Uranus are the two ice giants of our solar system.",
        image: "images/ice planet.jpeg"
      },
      {
        name: "Helium Planet",
        description: "A helium planet has an atmosphere that is predominantly made up of helium. Scientists believe such planets are formed after high temperatures of a nearby star cause the evaporation and disappearance of lighter gases including hydrogen and leave behind an atmosphere made up of helium. Due to the high concentration of helium in the atmosphere, helium planets are believed to be white and light-gray in appearance.",
        image: "images/helium planet.jpeg"
      },
      {
        name: "Gas Giant",
        description: "Gas giants are planets which are mainly made up of helium and hydrogen and other volatile compounds. These planets which exist in immense sizes are some of the largest known planets. Our solar system has two planets that are classified as gas giants, and these are Saturn and Jupiter. These planets are believed to have a molten rocky core. However, the properties of the compounds that exist in the cores of these gas giants are poorly understood due to the great temperatures and pressure.",
        image: "images/gas planet.jpeg"
      },
      {
        name: "Gas Dwarf",
        description: "A gas dwarf is a celestial body with a solid core but covered by a thick atmosphere made up of helium, hydrogen and other volatile gases. The gas dwarf is similar in composition to the gas giant planets and only differs in size. One example of a gas dwarf is Kepler-138d which is an extrasolar planet",
        image: "images/gas planet.jpeg"
      }
    // ... (more planet data)
];
