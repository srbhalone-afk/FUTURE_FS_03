# FUTURE_FS_03
Author - Saurabh Alone

import { MenuItem, ReviewItem, BakeStatusItem, BusinessInfo } from '../types';

export const BUSINESS_INFO: BusinessInfo = {
  name: "Copper & Oak",
  tagline: "Artisan Hearth Bakery & Specialty Espresso",
  subtagline: "36-Hour Wild Fermentation • 100% Organic Local Heritage Flour • Handcrafted Daily",
  story: "Founded in 2019 by master baker Elena Vance and specialty coffee roaster Marcus Cole, Copper & Oak began with a single wood-deck stone oven and an obsessive belief: honest bread requires only pure spring water, unbleached organic grains, sea salt, and patient wild fermentation. Every loaf spends 36 hours cold-fermenting to unlock complex aromas and natural digestibility before meeting the blazing stone hearth at dawn.",
  address: "42 Elmwood Avenue, Old Market Quarter",
  neighborhood: "Arts & Market District",
  city: "Downtown Metro",
  phone: "+15552345678",
  displayPhone: "(555) 234-5678",
  whatsapp: "+15552345678",
  email: "hello@copperoakbakery.com",
  hours: [
    { days: "Tuesday – Friday", open: "07:00", close: "16:30", note: "Hot Loaves at 07:15 & 11:30" },
    { days: "Saturday – Sunday", open: "07:30", close: "16:00", note: "Weekend Brunch & Pastry Specials" },
    { days: "Monday", open: "Closed", close: "Closed", note: "Weekly deep clean & sourdough feeding" },
  ],
  stats: [
    { label: "Wild Fermentation", value: "36 Hrs" },
    { label: "Organic Heritage Grains", value: "100%" },
    { label: "Community Rating", value: "4.9 ★" },
    { label: "Fresh Daily Batches", value: "650+" }
  ]
};

export const MENU_ITEMS: MenuItem[] = [
  {
    id: "bread-1",
    name: "Heritage Country Sourdough Loaf",
    category: "breads",
    description: "Our signature hearth loaf. Crisp, blistered caramel crust with an open, custardy crumb and balanced wild lactic tang. Naturally leavened.",
    price: 8.50,
    image: "https://images.unsplash.com/photo-1589367920969-ab8e050bbb04?auto=format&fit=crop&w=800&q=80",
    tags: ["Signature", "Customer Favorite", "Vegan"],
    isPopular: true,
    fermentationHours: 36,
    dietary: ["Vegan", "Vegetarian"],
    ingredients: ["Stone-ground organic wheat", "Spring water", "Dark rye sourdough starter", "Sea salt"],
    bakerNote: "Baked directly on stone at 485°F. Pair with salted butter or hearty soups."
  },
  {
    id: "bread-2",
    name: "Toasted Sesame & Danish Rye",
    category: "breads",
    description: "Dense, dark, nutrient-dense whole rye packed with toasted black and golden sesame seeds, sprouted rye berries, and malt.",
    price: 9.00,
    image: "https://images.unsplash.com/photo-1509440159596-0249088772ff?auto=format&fit=crop&w=800&q=80",
    tags: ["High Fiber", "Sprouted Grain"],
    fermentationHours: 48,
    dietary: ["Vegan", "Vegetarian"],
    ingredients: ["Whole organic dark rye", "Sprouted berries", "Toasted sesame", "Malt extract", "Sea salt"],
    bakerNote: "Cured for 24 hours before slicing. Ideal for open-faced smørrebrød."
  },
  {
    id: "bread-3",
    name: "Kalamata Olive & Rosemary Sourdough",
    category: "breads",
    description: "Infused with cold-pressed olive oil, fragrant fresh garden rosemary, and whole brined Greek Kalamata olives throughout.",
    price: 9.50,
    image: "https://images.unsplash.com/photo-1549931319-a545dcf3bc73?auto=format&fit=crop&w=800&q=80",
    tags: ["Savory Special"],
    isSeasonal: true,
    fermentationHours: 36,
    dietary: ["Vegan", "Vegetarian"],
    ingredients: ["Heritage white flour", "Kalamata olives", "Fresh rosemary", "Extra virgin olive oil", "Sea salt"],
    bakerNote: "Subtle herbaceous aroma released as the crust breaks."
  },
  {
    id: "bread-4",
    name: "Cinnamon Swirl & Golden Raisin Brioche",
    category: "breads",
    description: "Enriched with 84% butterfat Normandy cultured butter, free-range egg yolks, warm Ceylon cinnamon ribbons, and plump rum-soaked golden raisins.",
    price: 10.50,
    image: "https://images.unsplash.com/photo-1555939594-58d7cb561ad1?auto=format&fit=crop&w=800&q=80",
    tags: ["Weekend Special", "Sweet"],
    dietary: ["Vegetarian"],
    ingredients: ["Organic pastry flour", "Cultured butter", "Free-range eggs", "Ceylon cinnamon", "Golden raisins"],
    bakerNote: "Makes legendary French toast."
  },
  {
    id: "pastry-1",
    name: "Cardamom & Brown Butter Knot",
    category: "pastries",
    description: "Swedish-inspired twisted fika bun rolled with freshly stone-cracked green cardamom pods, caramelized butter, and raw pearl sugar crystals.",
    price: 4.75,
    image: "https://images.unsplash.com/photo-1509440159596-0249088772ff?auto=format&fit=crop&w=800&q=80",
    tags: ["Staff Pick", "Best Seller"],
    isPopular: true,
    dietary: ["Vegetarian"],
    ingredients: ["Laminated brioche dough", "Fresh green cardamom", "Cultured brown butter", "Raw pearl sugar"],
    bakerNote: "Crisp exterior, aromatic pillowy interior. Sells out by 11 AM."
  },
  {
    id: "pastry-2",
    name: "Double-Baked Almond Croissant",
    category: "pastries",
    description: "Our 72-layer butter croissant soaked in Madagascar vanilla bean syrup, filled with rich frangipane almond cream, and showered in toasted sliced almonds.",
    price: 5.50,
    image: "https://images.unsplash.com/photo-1555507036-ab1f4038808a?auto=format&fit=crop&w=800&q=80",
    tags: ["Signature Pastry"],
    isPopular: true,
    dietary: ["Vegetarian"],
    ingredients: ["Unbleached wheat", "Cultured butter", "Almond flour", "Bourbon vanilla syrup", "Toasted almonds"],
    bakerNote: "Double baked to achieve shattered-glass flaky texture."
  },
  {
    id: "pastry-3",
    name: "Valrhona Dark Chocolate Babka Bun",
    category: "pastries",
    description: "Twisted layered brioche laced with 70% dark single-origin Valrhona chocolate, hints of orange zest, and sea-salted fudge crumble.",
    price: 5.25,
    image: "https://images.unsplash.com/photo-1608198093002-ad4e005484ec?auto=format&fit=crop&w=800&q=80",
    tags: ["Rich Chocolate"],
    dietary: ["Vegetarian"],
    ingredients: ["Brioche", "Valrhona 70% chocolate", "Orange blossom", "Cocoa crumble"],
    bakerNote: "Subtly bitter chocolate balance, never overly cloying."
  },
  {
    id: "pastry-4",
    name: "Wild Berry & Meyer Lemon Morning Bun",
    category: "pastries",
    description: "Croissant pastry coil rolled in fragrant Meyer lemon sugar, bursting with simmered mountain blackberries and thyme syrup glaze.",
    price: 4.95,
    image: "https://images.unsplash.com/photo-1621236378699-8597fee6a1ce?auto=format&fit=crop&w=800&q=80",
    tags: ["Citrus & Berry"],
    isSeasonal: true,
    dietary: ["Vegetarian"],
    ingredients: ["Laminated dough", "Meyer lemon zest", "Oregon blackberries", "Thyme infusion"],
    bakerNote: "Tangy bright morning wake-up."
  },
  {
    id: "coffee-1",
    name: "Oak Reserve Flat White",
    category: "coffee",
    description: "Double shot of our seasonal Ethiopian Guji & Colombian washed espresso over silky, micro-textured steamed whole milk or oat milk.",
    price: 4.50,
    image: "https://images.unsplash.com/photo-1577968897966-3d4325b36b61?auto=format&fit=crop&w=800&q=80",
    tags: ["Barista Favorite"],
    isPopular: true,
    dietary: ["Vegetarian", "Gluten-Friendly"],
    ingredients: ["Espresso blend", "Steamed milk (or organic oat milk)"],
    bakerNote: "Tasting notes: Bergamot, honeysuckle, milk chocolate."
  },
  {
    id: "coffee-2",
    name: "Spanish Smoked Vanilla Cortado",
    category: "coffee",
    description: "Equal parts espresso and steamed milk touched with house-smoked Madagascar vanilla bean syrup and a dusting of grated nutmeg.",
    price: 4.75,
    image: "https://images.unsplash.com/photo-1514432324607-a09d9b4aefdd?auto=format&fit=crop&w=800&q=80",
    tags: ["Signature Drink"],
    dietary: ["Vegetarian", "Gluten-Friendly"],
    ingredients: ["Espresso", "House-smoked vanilla", "Steamed milk", "Nutmeg"],
    bakerNote: "Served in a warm Duralex glass."
  },
  {
    id: "coffee-3",
    name: "Kyoto Style 18-Hour Cold Drip",
    category: "coffee",
    description: "Single-origin Kenya Nyeri slow-dripped drop by drop over 18 hours. Exceptionally clear, liqueur-like sweetness with zero bitterness.",
    price: 5.25,
    image: "https://images.unsplash.com/photo-1517701550927-30cf4ba1dba5?auto=format&fit=crop&w=800&q=80",
    tags: ["Single Origin", "Slow Brew"],
    dietary: ["Vegan", "Gluten-Friendly", "Dairy-Free"],
    ingredients: ["Kenya Nyeri coffee beans", "Filtered ice water"],
    bakerNote: "Served over a hand-carved clear ice sphere."
  },
  {
    id: "coffee-4",
    name: "Ceremonial Uji Matcha Latte",
    category: "coffee",
    description: "First-harvest ceremonial grade organic matcha from Uji, Kyoto, whisked to a jade froth with warm oat milk and wild lavender blossom syrup.",
    price: 5.50,
    image: "https://images.unsplash.com/photo-1536256263959-770b48d82b0a?auto=format&fit=crop&w=800&q=80",
    tags: ["Antioxidant Rich", "Oat Milk Default"],
    dietary: ["Vegan", "Gluten-Friendly", "Dairy-Free"],
    ingredients: ["Uji ceremonial matcha", "Minor Figures oat milk", "Lavender syrup"],
    bakerNote: "Earthy, velvety, calming energy."
  },
  {
    id: "brunch-1",
    name: "Avocado & House Dukkah on Sourdough",
    category: "brunch",
    description: "Thick slice of toasted country sourdough, crushed Hass avocado, soft poached pasture egg, pickled shallots, Persian feta, and toasted hazelnut dukkah.",
    price: 14.50,
    image: "https://images.unsplash.com/photo-1525351484163-7529414344d8?auto=format&fit=crop&w=800&q=80",
    tags: ["Brunch Classic"],
    isPopular: true,
    dietary: ["Vegetarian"],
    ingredients: ["Country sourdough", "Hass avocado", "Poached organic egg", "Feta", "Nut dukkah"],
    bakerNote: "A neighborhood staple since opening day."
  },
  {
    id: "brunch-2",
    name: "Wild Mushroom & Gruyère Toastie",
    category: "brunch",
    description: "Cast-iron pressed sourdough filled with butter-sautéed chanterelles and cremini, aged cave Gruyère, thyme garlic confit, and Dijon mustard.",
    price: 15.00,
    image: "https://images.unsplash.com/photo-1528735602780-2552fd46c7af?auto=format&fit=crop&w=800&q=80",
    tags: ["Hot Pressed", "Comfort Food"],
    dietary: ["Vegetarian"],
    ingredients: ["Sourdough bread", "Chanterelles & cremini", "Cave-aged Gruyère", "Garlic confit"],
    bakerNote: "Melted cheese crust crispy edges guaranteed."
  },
  {
    id: "brunch-3",
    name: "Smoked Trout & Herb Labneh Plate",
    category: "brunch",
    description: "Locally oak-smoked rainbow trout, whipped mint and dill labneh, thinly shaved breakfast radish, caper berries, and warm toasted Danish rye slices.",
    price: 16.50,
    image: "https://images.unsplash.com/photo-1546069901-ba9599a7e63c?auto=format&fit=crop&w=800&q=80",
    tags: ["Chef Special"],
    dietary: ["Nut-Free"],
    ingredients: ["Smoked trout", "House labneh", "Dill & mint", "Pickled capers", "Seeded rye"],
    bakerNote: "Light, protein-rich, beautifully balanced."
  },
  {
    id: "pantry-1",
    name: "Copper & Oak Wild Sourdough Starter (Live)",
    category: "pantry",
    description: "Take home our legendary 7-year-old sourdough mother 'Matilda'. Includes active bubbling starter in a Mason jar + feeding guide booklet.",
    price: 12.00,
    image: "https://images.unsplash.com/photo-1509440159596-0249088772ff?auto=format&fit=crop&w=800&q=80",
    tags: ["Take Home", "Bake at Home"],
    dietary: ["Vegan"],
    ingredients: ["Organic rye flour", "Spring water", "Wild microflora"],
    bakerNote: "Fed twice daily since 2019. Vigorous and forgiving."
  },
  {
    id: "pantry-2",
    name: "Fig, Bourbon & Vanilla Bean Jam (250g)",
    category: "pantry",
    description: "Small-batch copper pot jam made from ripe Black Mission figs, Kentucky bourbon reduction, and organic Tahitian vanilla pods.",
    price: 9.50,
    image: "https://images.unsplash.com/photo-1589301760014-d929f3979dbc?auto=format&fit=crop&w=800&q=80",
    tags: ["Small Batch"],
    dietary: ["Vegan", "Gluten-Friendly"],
    ingredients: ["Mission figs", "Cane sugar", "Bourbon reduction", "Tahitian vanilla", "Lemon juice"],
    bakerNote: "Incredible pairing with goat cheese and toasted sourdough."
  }
];

export const BAKE_STATUS_ITEMS: BakeStatusItem[] = [
  { name: "Country Sourdough", status: "Ready Now", timeAgo: "Out of hearth 20m ago", percentageLeft: 85 },
  { name: "Cardamom & Brown Butter Knots", status: "Ready Now", timeAgo: "Fresh tray", percentageLeft: 60 },
  { name: "Double-Baked Almond Croissants", status: "Ready Now", timeAgo: "Glazed & cooling", percentageLeft: 40 },
  { name: "Kalamata Olive Hearth Loaves", status: "Coming at 10:30 AM", timeAgo: "Proofing in baskets" },
  { name: "Whole Grain Danish Rye", status: "Fresh Batch Cooling", timeAgo: "Resting on racks", percentageLeft: 95 },
];

export const REVIEWS: ReviewItem[] = [
  {
    id: "rev-1",
    author: "Claire Moreau",
    rating: 5,
    date: "3 days ago",
    source: "Google",
    favoriteItem: "Cardamom Knot & Flat White",
    quote: "I've lived in Paris and Copenhagen, and the laminated pastries here genuinely rival the best in Europe. The cardamom knot alone is worth waking up at 7am for. Having pre-ordering online now makes weekend mornings so effortless!",
    avatar: "https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=200&q=80"
  },
  {
    id: "rev-2",
    author: "David K. Henderson",
    rating: 5,
    date: "1 week ago",
    source: "Google",
    favoriteItem: "Heritage Country Sourdough",
    quote: "Real sourdough is hard to find. Most supermarket bread gives me bloating, but Elena's 36-hour slow fermented loaves are so gentle and flavorful. The crust crunch is acoustic perfection. Truly the heart of our neighborhood.",
    avatar: "https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&w=200&q=80"
  },
  {
    id: "rev-3",
    author: "Maya Patel",
    rating: 5,
    date: "2 weeks ago",
    source: "Local Guide",
    favoriteItem: "Avocado & Dukkah Toastie",
    quote: "We ordered 4 pastry boxes and 2 catering carafes for our architectural studio's client presentation. Every single person asked where the food was from. Clean website, fast order pickup, and impeccable quality.",
    avatar: "https://images.unsplash.com/photo-1517841905240-472988babdf9?auto=format&fit=crop&w=200&q=80"
  }
];

export const FAQS = [
  {
    q: "Can I preorder bread or pastries for morning pickup?",
    a: "Yes! Use the 'Preorder Bag' on this website to order up to 3 days in advance or by 6:00 PM the night before. Your loaf will be sliced (if requested), bagged, and waiting at our express counter so you can skip the morning line."
  },
  {
    q: "Do you offer gluten-free or vegan options?",
    a: "All our sourdough breads are naturally 100% vegan (water, flour, wild starter, salt). We also offer oat milk for all coffees and specific vegan and gluten-friendly savory and pastry items clearly marked on the menu."
  },
  {
    q: "Can I reserve a table for weekend brunch?",
    a: "We accept table reservations for parties of 2 to 8 guests via our Reserve button. We also hold 40% of our indoor and sunny courtyard seating for walk-in community guests."
  },
  {
    q: "Do you cater for office breakfasts or private events?",
    a: "Yes! We specialize in morning bakery boxes, coffee carafes, and artisan sandwich platters for 10 to 80 people. You can submit a catering inquiry directly through our website form."
  }
];

export const PITCH_DECK_DATA = {
  clientName: "Elena & Marcus (Owners of Copper & Oak)",
  businessCategory: "Artisan Bakery & Specialty Café",
  problemStatements: [
    {
      icon: "phone-off",
      title: "Morning Phone Bottlenecks",
      desc: "During 7:30 - 9:30 AM rush, staff cannot answer the phone. Customers asking 'Do you have sourdough left?' or wanting to hold 2 loaves get busy signals or walk away."
    },
    {
      icon: "search",
      title: "Invisible to High-Intent Google Searches",
      desc: "Without a modern SEO-optimized website, nearby residents and weekend tourists searching 'best sourdough near me' or 'bakery breakfast' find competitors with active web pages instead of an Instagram-only account."
    },
    {
      icon: "shopping-bag",
      title: "Lost High-Ticket Catering & Preorders",
      desc: "Local corporate offices and weekend brunches want to order 4-6 pastry boxes ($80-$160 each), but have no simple digital form or menu to share with their finance team."
    },
    {
      icon: "dollar-sign",
      title: "Delivery App Commissions Drain Margins",
      desc: "Third-party delivery platforms take 25%-30% commission. Direct online pickup preorders preserve 100% of the bakery's margins."
    }
  ],
  packages: [
    {
      tier: "Local Web Presence Starter",
      price: "$650",
      type: "One-Time Setup",
      bestFor: "Solo cafés & boutique shops wanting an immediate, credible brand website",
      deliverables: [
        "Modern Mobile-First Responsive Website",
        "Interactive Menu with Dietary Tags & Allergens",
        "Google Maps & Directions Integration",
        "1-Click WhatsApp & Phone Call Action Buttons",
        "Story & Sourcing Showcase + Photo Gallery",
        "Google Business Profile Link & Schema Markup"
      ],
      developerNote: "Takes 2-3 days to build. 80%+ profit margin."
    },
    {
      tier: "Growth & Preorders Suite",
      price: "$1,250",
      recurring: "+ $95 / month",
      featured: true,
      bestFor: "High-volume bakeries, cafés & restaurants ready to monetize digital sales",
      deliverables: [
        "Everything in Starter, PLUS:",
        "Direct Online Preorder Bag & Pickup Workflow",
        "Live 'Fresh Out of Oven' Bake Status Tracker",
        "Table Reservation & Catering Inquiry Engine",
        "Local SEO Keyword Optimization for your neighborhood",
        "Monthly Menu & Pricing updates + Hosting included",
        "Automated WhatsApp notification alerts for new orders"
      ],
      developerNote: "Standard agency rate. The $95/mo recurring fee creates predictable passive retainer income!"
    },
    {
      tier: "Complete Omnichannel Retainer",
      price: "$2,400",
      recurring: "+ $250 / month",
      bestFor: "Expanding local brands with catering, merchandise & events",
      deliverables: [
        "Everything in Growth, PLUS:",
        "Online Shop for Coffee Beans & Merch",
        "Email / SMS VIP Club for Secret Weekend Bakes",
        "High-Resolution Food Photography direction",
        "Bi-weekly SEO monitoring & Google Review booster",
        "Dedicated Developer on WhatsApp for urgent changes"
      ],
      developerNote: "High-value partnership. Retain 3 clients like this = $750/mo steady recurring baseline."
    }
  ]
};
