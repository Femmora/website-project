// ---------- 50+ PRODUCTS (same as before, but colors adjusted in CSS) ----------
const PRODUCTS_STORAGE_KEY = 'femmoraProducts_v3';
const categoryList = ['necklace', 'ring', 'bracelet', 'earring', 'anklet'];

// Edit this list to update the Discover All Jewelry section.
// Change image paths, titles, prices, categories, descriptions, material, and care text.
const customCatalog = [
  {
    id: 1,
    name: 'Knot gold bracelet',
    price: 80.00,
    category: 'Bracelets',
    originalCategory: 'Bracelets',
    isPearl: false,
    image: 'pics/2.jpg',
    hoverImg: 'pics/2.jpg',
    isNew: true,
    bestSeller: true,
    rating: 4.8,
    description: 'Minimal gold bracelet with elegant knot detail for daily wear.',
    material: 'Stainless steel with gold plating',
    care: 'Store dry, avoid moisture and chemicals.'
  },
  {
    id: 2,
    name: 'Twist ring',
    price: 40.00,
    category: 'Rings',
    originalCategory: 'Rings',
    isPearl: true,
    image: 'pics/the%20second.jpg',
    hoverImg: 'pics/the%20second.jpg',
    isNew: true,
    bestSeller: true,
    rating: 4.7,
    description: 'Modern twist ring with a unique design.',
    material: 'Stainless steel with gold plating',
    care: 'Store dry,avoid water and perfumes.'
  },
  {
    id: 3,
    name: 'Pearl drop necklace',
    price: 100.00,
    category: 'Necklaces',
    originalCategory: 'Necklaces',
    isPearl: false,
    image: 'pics/discover all.jpg',
    hoverImg: 'pics/discover all.jpg',
    isNew: true,
    bestSeller: false,
    rating: 4.5,
    description: 'Delicate pearl drop necklace for a touch of elegance.',
    material: 'Gold plated, stainless steel and faux pearl',
    care: 'Avoid contact with water and perfume.'
  },
  {
    id: 4,
    name: 'V Shape Crystal Necklace',
    price: 130.00,
    category: 'necklace',
    originalCategory: 'necklace',
    isPearl: false,
    image: 'pics/the%204th.jpg',
    hoverImg: 'pics/the%204th.jpg',
    isNew: true,
    bestSeller: false,
    rating: 4.6,
    description: 'Modern V-shaped necklace adorned with sparkling crystals, perfect for a chic and sophisticated style.',
    material: 'Alloy, silver plated, zirconia crystals',
    care: 'Keep dry and store in a soft pouch.'
  },
  {
    id: 5,
    name: 'Rose stud earrings',
    price: 60.00,
    category: 'Earrings',
    originalCategory: 'Earrings',
    isPearl: false,
    image: 'pics/the%205th.jpg',
    hoverImg: 'pics/the%205th.jpg',
    isNew: true,
    bestSeller: false,
    rating: 4.6,
    description: 'Floral stud earrings with soft feminine elegance.',
    material: 'Alloy, gold plated',
    care: 'Protect from moisture and harsh chemicals.'
  },
  {
    id: 6,
    name: 'Hand chain ',
    price: 55.00,
    category: 'Bracelets',
    originalCategory: 'Bracelets',
    isPearl: false,
    image: 'https://i.pinimg.com/736x/b1/e2/3f/b1e23fae486c79ff4ea3c6b869246722.jpg',
    hoverImg: 'https://i.pinimg.com/736x/b1/e2/3f/b1e23fae486c79ff4ea3c6b869246722.jpg',
    isNew: true,
    bestSeller: true,
    rating: 4.4,
    description: 'hand chain with heart charms for everyday wear.',
    material: 'stainless steel,gold plated',
    care: 'Store in a dry place away from sunlight.'
  },
  {
    id: 7,
    name: 'Pearl hoop earrings',
    price: 70.00,
    category: 'Earrings',
    originalCategory: 'Earrings',
    isPearl: false,
    image: 'pics/the%207th.jpg',
    hoverImg: 'pics/the%207th.jpg',
    isNew: true,
    bestSeller: false,
    rating: 4.7,
    description: 'Twisted hoop earrings with elgant pearl details.',
    material: 'Stainless steel, gold plated, pearl details',
    care: 'Avoid rubbing and keep in protective storage.'
  },
  {
    id: 8,
    name: 'Daisy pendant necklace',
    price: 90.00,
    category: 'Necklaces',
    originalCategory: 'Necklaces',
    isPearl: true,
    image: 'pics/the%208th.jpg',
    hoverImg: 'pics/the%208th.jpg',
    isNew: true,
    bestSeller: true,
    rating: 4.6,
    description: 'Cute floral necklace witj a crystal center.',
    material: 'Gold plated, stainless steel and crystal',
    care: 'Store dry, avoid moistre and perfumes.'
  },
  {
    id: 9,
    name: 'Double Pearl Drop Necklace',
    price: 150.00,
    category: 'Necklaces',
    originalCategory: 'Necklaces',
    isPearl: true,
    image: 'pics/1.jpg',
    hoverImg: 'pics/1.jpg',
    isNew: false,
    bestSeller: false,
    rating: 4.7,
    description: 'Elegant layered necklace featuring delicate chains and a single pearl drop for a refined and graceful look.',
    material: 'Gold plated alloy with freshwater pearls',
    care: 'Avoid contact with water, perfumes, and chemicals. Store in a dry place.'
  },
  {
    id: 10,
    name: 'Gold Bow Earrings',
    price: 50.00,
    category: 'Earrings',
    originalCategory: 'Earrings',
    isPearl: false,
    image: 'pics/3.jpg',
    hoverImg: 'pics/3.jpg',
    isNew: false,
    bestSeller: false,
    rating: 4.5,
    description: 'Charming bow-shaped earrings that add a cute and feminine accent to any outfit.',
    material: 'Alloy, gold plated ',
    care: 'Keep away from moisture and clean with a soft cloth.'
  },
  {
    id: 11,
    name: 'Gold Charm Bracelet',
    price: 90.00,
    category: 'Bracelets',
    originalCategory: 'Bracelets',
    isPearl: false,
    image: 'pics/4.jpg',
    hoverImg: 'pics/4.jpg',
    isNew: false,
    bestSeller: false,
    rating: 4.8,
    description: 'Subtle charm and pearl bracelet for everyday layering.',
    material: 'Alloy, gold plated with pearls',
    care: 'Wipe with a soft cloth after wear.'
  },
  {
    id: 12,
    name: 'Minimal Beaded Necklace',
    price: 70.00,
    category: 'Necklaces',
    originalCategory: 'Necklaces',
    isPearl: true,
    image: 'pics/5.jpg',
    hoverImg: 'pics/5.jpg',
    isNew: false,
    bestSeller: false,
    rating: 4.9,
    description: 'Simple and modern necklace with tiny beads for everyday elegance.',
    material: ' Alloy, gold plated, pearl accents',
    care: 'Store separately to prevent scratches.'
  },
  {
    id: 13,
    name: 'Heart Pendant Necklace with pearl',
    price: 120.00,
    category: 'Necklaces',
    originalCategory: 'Necklaces',
    isPearl: true,
    image: 'pics/6.jpg',
    hoverImg: 'pics/6.jpg',
    isNew: false,
    bestSeller: false,
    rating: 4.6,
    description: 'Romantic heart pendant necklace that adds a soft and feminine charm.',
    material: 'Alloy, gold plated, pearl',
    care: 'Avoid water and chemicals when worn.'
  },
  {
    id: 14,
    name: 'Flower necklace',
    price: 65.00,
    category: 'Necklaces',
    originalCategory: 'Necklaces',
    isPearl: false,
    image: 'pics/7.jpg',
    hoverImg: 'pics/7.jpg',
    isNew: false,
    bestSeller: false,
    rating: 4.3,
    description: 'Elegant flower necklace symbolizing beauty and natural grace..',
    material: 'Alloy, gold plated, zircon',
    care: 'Clean gently with a dry cloth.'
  },
  {
    id: 15,
    name: 'Crystal Band Ring',
    price: 75.00,
    category: 'Rings',
    originalCategory: 'Rings',
    isPearl: false,
    image: 'pics/8.jpg',
    hoverImg: 'pics/8.jpg',
    isNew: false,
    bestSeller: false,
    rating: 4.4,
    description: 'Classic ring with embedded crystals for a luxurious sparkle.',
    material: 'Alloy, gold plated, zirconia crystals',
    care: 'Remove before swimming or showering.'
  },
  {
    id: 16,
    name: 'Heart Pendant Necklace',
    price: 80.00,
    category: 'Necklaces',
    originalCategory: 'Necklaces',
    isPearl: true,
    image: 'pics/9.jpg',
    hoverImg: 'pics/9.jpg',
    isNew: false,
    bestSeller: false,
    rating: 4.7,
    description: 'Romantic heart pendant necklace with a delicate pearl, adding a soft and feminine charm.',
    material: 'Freshwater pearl and gold plated chain',
    care: 'Store separately from other jewelry.'
  },
  {
    id: 17,
    name: 'Pearl stand earrings',
    price: 90.00,
    category: 'Earrings',
    originalCategory: 'Earrings',
    isPearl: true,
    image: 'pics/10.jpg',
    hoverImg: 'pics/10.jpg',
    isNew: false,
    bestSeller: true,
    rating: 4.9,
    description: 'Classic pearl choker with luxe finishing.',
    material: 'Freshwater pearls, gold clasp',
    care: 'Keep dry and avoid heavy perfume.'
  },
  {
    id: 18,
    name: 'Gold Cuff Bracelet',
    price: 55.00,
    category: 'Bracelets',
    originalCategory: 'Bracelets',
    isPearl: false,
    image: 'pics/11.jpg',
    hoverImg: 'pics/11.jpg',
    isNew: false,
    bestSeller: false,
    rating: 4.5,
    description: 'Modern open cuff bracelet with a sleek and minimal design.',
    material: 'Gold plated stainless steel',
    care: 'Store in a jewelry box to prevent dulling.'
  },
  {
    id: 19,
    name: 'Pearl & Gold Statement Earrings',
    price: 120.00,
    category: 'Earrings',
    originalCategory: 'Earrings',
    isPearl: true,
    image: 'pics/12.jpg',
    hoverImg: 'pics/12.jpg',
    isNew: false,
    bestSeller: true,
    rating: 4.8,
    description: 'Bold statement earrings with pearl accents.',
    material: 'Pearl and gold plated alloy',
    care: 'Handle gently and keep in a safe box.'
  },
  {
    id: 20,
    name: 'Delicate crystal ring',
    price: 65.00,
    category: 'Rings',
    originalCategory: 'Rings',
    isPearl: false,
    image: 'pics/20.jpg',
    hoverImg: 'pics/20.jpg',
    isNew: false,
    bestSeller: false,
    rating: 4.6,
    description: 'Fine ring with small crystals for a subtle and feminine sparkle.',
    material: 'Crystal and gold plated alloy',
    care: 'Remove before sleeping or showering.'
  }
];

const productNames = {
  necklace: ['Delicate Chain Necklace', 'Pearl Pendant Necklace', 'Gold Bar Necklace', 'Initial Necklace', 'Charm Necklace', 'Layered Chain Necklace', 'Crystal Teardrop Necklace', 'Heart Locket Necklace', 'Saturn Necklace', 'Beaded Choker'],
  ring: ['Stackable Gold Ring', 'Pearl Accent Ring', 'Eternity Band', 'Minimalist Wave Ring', 'Diamond Cut Ring', 'Twist Band Ring', 'Opal Stone Ring', 'Signet Ring', 'Adjustable Pearl Ring', ' Ring'],
  bracelet: ['Thin Chain Bracelet', 'Pearl Beaded Bracelet', 'Tennis Bracelet', 'Charm Bracelet', 'Bangle Set', 'Cuff Bracelet', 'Heart Clasp Bracelet', 'Beaded Stretch Bracelet', 'Gold Mesh Bracelet', 'Adjustable Rope Bracelet'],
  earring: ['Pearl Stud Earrings', 'Hoop Earrings', 'Drop Pearl Earrings', 'Crystal Chandelier', 'Geometric Studs', 'Tassel Earrings', 'Chain Link Earrings', 'Mini Circle Hoops', 'Pearl Climbers', 'Floral Drop Earrings'],
  anklet: ['Delicate Anklet', 'Pearl Anklet', 'Gold Bead Anklet', 'Charm Anklet', 'Chain Anklet with Shell', 'Adjustable Pearl Anklet', 'Boho Anklet', 'Tiny Heart Anklet', 'Crystal Anklet', 'Multi-layered Anklet']
};

function generateProductData() {
  const specificProducts = [
    { name: 'Delicate Chain Necklace', price: 100, image: 'pics/the%20first.jpg' },
    { name: 'Pearl Pendant Necklace', price: 109, image: 'pics/the%20second.jpg' },
    { name: 'Gold Bar Necklace', price: 58, image: 'pics/the%203ed.jpg' },
    { name: 'Initial Necklace', price: 59, image: 'pics/the%204th.jpg' },
    { name: 'Charm Necklace', price: 112, image: 'pics/the%205th.jpg' },
    { name: 'Layered Chain Necklace', price: 133, image: 'pics/the%206th.jpg' },
    { name: 'Crystal Teardrop Necklace', price: 115, image: 'pics/the%207th.jpg' },
    { name: 'Heart Locket Necklace', price: 112, image: 'pics/the%208th.jpg' }
  ];

  let products = [];
  let idCounter = 1;

  // Generate the specific new arrivals products
  specificProducts.forEach((prod, index) => {
    products.push({
      id: idCounter++,
      name: prod.name,
      price: prod.price,
      category: 'necklace',
      originalCategory: 'necklace',
      isPearl: prod.name.toLowerCase().includes('pearl'),
      image: prod.image,
      hoverImg: prod.image,
      isNew: true,
      bestSeller: index < 4, // First 4 are best sellers
      rating: 4.5 + (index * 0.1), // Varying ratings
      description: `Beautiful ${prod.name.toLowerCase()} crafted with premium materials. Perfect for everyday elegance.`,
      material: prod.name.toLowerCase().includes('pearl') ? "Freshwater pearl with 14k gold plating" : "Stainless steel, gold plated",
      care: "Store dry, avoid chemicals, keep away from moisture."
    });
  });

  // Add more products for the full catalog
  const additionalImages = [
    'pics/10574d3bf0a4c97f7b6470131cb28578.jpg',
    'pics/14bb8320afdadbccf556dae85885f86e.jpg',
    'pics/19c48f9f57d50e0df49c5d628701a178.jpg',
    'pics/23d23c394867431b0780b5eed3283b25.jpg',
    'pics/23e965cb1520f8ebad965fdd175c57c9.jpg',
    'pics/2ee73bae4fe526942cb8cb4d57bdca13.jpg',
    'pics/5120362dad5938eb0bea1361adca6732.jpg',
    'pics/724aa47f3e05ceca54406b2771b8be22.jpg',
    'pics/787e4684512cf5dcfd2826c0e3405587.jpg',
    'pics/7bce25fc96118fc5c96e03d7ef775c30.jpg',
    'pics/7c83ada281e7897f186f0af48b69bf65.jpg',
    'pics/86135640d37db74717ec6f1bbb08793f.jpg',
    'pics/871ae88664cfb5999734201f92e59473.jpg',
    'pics/a7d18888b6ca0974b003cff86a8f9406.jpg',
    'pics/ad9a3d1e4ca1a2e06e33615750e87bc9.jpg',
    'pics/b1e23fae486c79ff4ea3c6b869246722.jpg',
    'pics/b232cd35f80c0f23aec82de4de770eb5.jpg',
    'pics/b8307e8bfbc8a7347d16acb57eceb590.jpg',
    'pics/ccc7dd0ef312ed232a6bc7653b673a8c.jpg'
  ];

  const fixedPrices = {
    necklace: [100, 109, 58, 59, 120, 112, 115, 105, 73, 99],
    ring: [151, 84, 87, 86, 124, 149, 118, 45, 50, 68],
    bracelet: [89, 137, 78, 105, 89, 131, 132, 74, 102, 109],
    earring: [52, 159, 141, 53, 151, 84, 87, 100, 52, 127],
    anklet: [73, 112, 108, 84, 104, 46, 110, 96, 53, 93]
  };

  for (let cat of categoryList) {
    for (let i = 0; i < 10; i++) {
      let name = productNames[cat][i % productNames[cat].length];
      let isPearl = name.toLowerCase().includes('pearl') || (cat === 'earring' && i % 3 === 0) || (cat === 'necklace' && i % 4 === 1);
      let price = fixedPrices[cat][i % fixedPrices[cat].length];
      let rating = [4.8, 4.5, 4.6, 4.9, 4.3, 4.7, 4.4, 4.2, 4.8, 4.6][i % 10];
      let imageIndex = (idCounter - 9) % additionalImages.length; // Start after the 8 new arrivals
      let finalImage = additionalImages[imageIndex];

      products.push({
        id: idCounter,
        name: name,
        price: price,
        category: isPearl ? 'pearl' : cat,
        originalCategory: cat,
        isPearl: isPearl,
        image: finalImage,
        hoverImg: finalImage,
        isNew: false, // Only the first 8 are new
        bestSeller: (idCounter % 5 === 0) || (rating > 4.7 && idCounter > 20),
        rating: parseFloat(rating.toFixed(1)),
        description: `Beautiful ${name.toLowerCase()} crafted with premium materials. Perfect for everyday elegance.`,
        material: isPearl ? "Freshwater pearl with 14k gold plating" : "Stainless steel, gold plated",
        care: "Store dry, avoid chemicals, keep away from moisture."
      });
      idCounter++;
    }
  }

  const extraPearls = [
    { name:"Classic Pearl Strand Necklace", price:89, category:"pearl", isPearl:true, rating:4.9, image:"pics/GG.main.0.2.jpeg" },
    { name:"Baroque Pearl Earrings", price:54, category:"pearl", isPearl:true, rating:4.8, image:"pics/10574d3bf0a4c97f7b6470131cb28578.jpg" },
    { name:"Pearl & Crystal Bracelet", price:67, category:"pearl", isPearl:true, rating:4.7, image:"pics/14bb8320afdadbccf556dae85885f86e.jpg" },
    { name:"Pearl Anklet with Gold Chain", price:48, category:"pearl", isPearl:true, rating:4.8, image:"pics/19c48f9f57d50e0df49c5d628701a178.jpg" }
  ];

  extraPearls.forEach((p) => {
    products.push({
      id: idCounter++,
      ...p,
      isNew: false,
      bestSeller: true,
      material: "Freshwater pearl, gold-filled",
      care: "Avoid chemicals, store in pouch",
      description: `Gorgeous ${p.name.toLowerCase()} with rich pearl accents.`
    });
  });

  return products.slice(0, 55);
}

function loadProducts() {
  let stored = localStorage.getItem(PRODUCTS_STORAGE_KEY);
  if (stored) {
    try {
      const parsed = JSON.parse(stored);
      const valid = Array.isArray(parsed) && parsed.length >= 8 && parsed.every(item => item && item.image && typeof item.image === 'string' && item.image.length > 0);
      if (valid) return parsed;
      console.warn('Cached product data invalid or outdated, regenerating.');
    } catch (e) {
      console.warn('Invalid stored products, regenerating.', e);
    }
  }
  const generated = generateProductData();
  localStorage.setItem(PRODUCTS_STORAGE_KEY, JSON.stringify(generated));
  return generated;
}

let products = loadProducts();
// Cart & global functions (unchanged but using updated color variables)
let cart = [];
let currentLanguage = 'en';

function applyLanguage(lang) {
  document.querySelectorAll('[data-lang-en][data-lang-fr]').forEach(el => {
    el.innerText = lang === 'en' ? el.getAttribute('data-lang-en') : el.getAttribute('data-lang-fr');
  });
  currentLanguage = lang;
}

document.getElementById('languageSwitcher').addEventListener('change', (e) => applyLanguage(e.target.value));

const accountModal = document.getElementById('accountModal'), accountBtn = document.getElementById('accountBtn'), closeAccountModal = document.getElementById('closeAccountModal');
accountBtn.addEventListener('click', () => { accountModal.classList.remove('invisible','opacity-0'); });
function closeAccount() { accountModal.classList.add('invisible','opacity-0'); }
closeAccountModal.addEventListener('click', closeAccount);
accountModal.addEventListener('click', (e) => { if(e.target === accountModal) closeAccount(); });

function updateCartUI() { 
  let total = cart.reduce((sum,i)=>sum+i.price*i.qty,0); 
  document.getElementById('cartCount').innerText=cart.reduce((s,i)=>s+i.qty,0); 
  document.getElementById('cartTotal').innerText=`$${total.toFixed(2)}`; 
  let container=document.getElementById('cartItemsList'); 
  if(!container)return; 
  container.innerHTML=cart.map((item,idx)=>`<div class="flex justify-between items-center border-b border-[#F3E0D4] pb-2"><div><p class="font-medium text-[#5A3E35]">${item.name}</p><p class="text-sm text-gray-500">Qty:${item.qty} x $${item.price}</p></div><div><button class="remove-item text-rose-400" data-index="${idx}"><i class="fas fa-trash-alt"></i></button></div></div>`).join(''); 
  document.querySelectorAll('.remove-item').forEach(btn=>btn.addEventListener('click',(e)=>{let i=parseInt(btn.dataset.index); cart.splice(i,1); updateCartUI(); saveCart();}));
}

function saveCart(){ localStorage.setItem('femmoraCart',JSON.stringify(cart)); updateCartUI(); }

function addToCart(product, qty=1){ 
  let existing=cart.find(p=>p.id===product.id); 
  if(existing) existing.qty+=qty; 
  else cart.push({...product,qty}); 
  updateCartUI(); 
  saveCart(); 
  showToast(`✨ ${product.name} added`); 
  addCartAnimation(); 
}

function addCartAnimation(){ 
  let btn=document.createElement('div'); 
  btn.innerHTML='+1'; 
  btn.className='fixed bottom-8 right-8 bg-[#E1B28D] text-white px-4 py-2 rounded-full shadow-lg z-50 text-sm font-bold toast-notif'; 
  document.body.appendChild(btn); 
  setTimeout(()=>btn.remove(),1200);
}

function showToast(msg){
  let t=document.createElement('div'); 
  t.innerText=msg; 
  t.className='fixed bottom-8 left-1/2 -translate-x-1/2 bg-black/70 text-white px-5 py-2 rounded-full z-50 text-sm toast-notif'; 
  document.body.appendChild(t); 
  setTimeout(()=>t.remove(),1800);
}

function openProductModal(product){ 
  let modal=document.getElementById('productModal'); 
  document.getElementById('modalContent').innerHTML=`<div><img src="${product.image}" class="rounded-xl w-full object-cover"><div class="flex gap-2 mt-2"><img src="${product.hoverImg||product.image}" class="w-16 h-16 rounded-md"></div></div><div><h2 class="font-serif text-2xl text-[#5A3E35]">${product.name}</h2><p class="text-2xl font-semibold text-[#D9A77A] mt-1">$${product.price}</p><div class="mt-3"><label class="text-[#5A3E35]">Size</label><select id="modalSize" class="border border-[#F3E0D4] rounded px-3 py-1"><option>One Size</option><option>Adjustable</option></select></div><div class="mt-3"><label class="text-[#5A3E35]">Qty</label><input id="modalQty" type="number" value="1" min="1" class="border border-[#F3E0D4] w-20 rounded px-2"></div><button id="modalAddToCartBtn" class="mt-4 bg-[#5A3E35] text-white w-full py-2 rounded-full hover:bg-[#D9A77A] transition">Add to Cart</button><p class="mt-4 text-sm text-gray-600">${product.description}</p><p class="text-xs mt-2 text-gray-500"><strong>Material:</strong> ${product.material}</p><p class="text-xs text-gray-500"><strong>Care:</strong> ${product.care}</p></div>`; 
  document.getElementById('modalAddToCartBtn').onclick=()=>{let qty=parseInt(document.getElementById('modalQty').value); addToCart(product,qty); document.getElementById('productModal').classList.add('invisible','opacity-0');}; 
  modal.classList.remove('invisible','opacity-0');
}

function closeModal(){ document.getElementById('productModal').classList.add('invisible','opacity-0');}

function renderStars(rating) { 
  let full = Math.floor(rating); 
  let half = rating % 1 >= 0.5; 
  let empty = 5 - full - (half?1:0); 
  return '<i class="fas fa-star star-filled"></i>'.repeat(full)+(half?'<i class="fas fa-star-half-alt star-filled"></i>':'')+'<i class="far fa-star text-gray-300"></i>'.repeat(empty); 
}

function renderNewArrivals(){ 
  let newItems=customCatalog.filter(p=>p.isNew===true).slice(0,8); 
  let grid=document.getElementById('newArrivalsGrid'); 
  grid.innerHTML=newItems.map(p=>`<div class="product-card bg-white rounded-2xl overflow-hidden shadow-md cursor-pointer" data-id="${p.id}"><div class="relative"><img src="${p.image}" class="w-full h-64 object-cover"><span class="absolute top-3 left-3 bg-[#E1B28D] text-white text-xs px-2 py-1 rounded-full">NEW</span></div><div class="p-4 text-center"><h3 class="font-semibold text-[#5A3E35]">${p.name}</h3><p class="text-[#D9A77A] font-bold">$${p.price}</p><button class="view-detail mt-2 text-sm underline text-[#D9A77A]">Quick View</button></div></div>`).join(''); 
  attachProductCardEvents();
}

function renderBestSellerSlider(){ 
  let best=products.filter(p=>p.bestSeller).slice(0,12); 
  let track=document.getElementById('bestSellerSliderTrack'); 
  track.innerHTML=best.map(p=>`<div class="min-w-[250px] w-[260px] flex-shrink-0"><div class="bg-white rounded-2xl shadow-md p-3 cursor-pointer transition hover:-translate-y-0.5 hover:shadow-lg" data-id="${p.id}"><img src="${p.image}" class="h-44 w-full object-cover rounded-xl border border-[#D9A77A]"><div class="mt-2 text-center"><p class="font-semibold text-[#5A3E35]">${p.name}</p><div class="flex justify-center text-xs">${renderStars(p.rating)}</div><p class="font-bold text-[#D9A77A]">$${p.price}</p></div></div></div>`).join(''); 
  document.querySelectorAll('#bestSellerSliderTrack [data-id]').forEach(el=>el.addEventListener('click',(e)=>openProductModal(products.find(p=>p.id==parseInt(el.dataset.id)))));
}

function attachProductCardEvents(){ 
  document.querySelectorAll('.product-card').forEach(card=>{
    card.addEventListener('click',(e)=>{
      let id=parseInt(card.dataset.id); 
      let prod = customCatalog.find(p => p.id === id) || products.find(p => p.id === id);
      if(prod) openProductModal(prod);
    });
  }); 
  document.querySelectorAll('.view-detail').forEach(btn=>btn.addEventListener('click',(e)=>{e.stopPropagation();}));
}

function renderFilteredGrid(customFilterCategory = null){ 
  let search=document.getElementById('searchInput').value.toLowerCase(); 
  let cat = customFilterCategory !== null ? customFilterCategory : document.getElementById('categoryFilter').value; 
  let maxPrice=parseInt(document.getElementById('priceFilter').value); 
  let filtered=customCatalog.filter(p=>p.name.toLowerCase().includes(search)&&(cat==='all'||p.category===cat)&&p.price<=maxPrice).slice(0,20); 
  let container=document.getElementById('filteredProductsGrid'); 
  if (filtered.length === 0) {
    container.innerHTML = `<div class="col-span-1 sm:col-span-2 lg:col-span-4 text-center text-gray-500">No products match your search. Try another term or reset the filters.</div>`;
  } else {
    container.innerHTML=filtered.map(p=>`<div class="bg-white rounded-2xl shadow-md p-3 cursor-pointer transition" data-id="${p.id}"><img src="${p.image}" class="h-56 w-full object-cover rounded-xl border border-[#D9A77A]"><div class="mt-2 text-center"><p class="font-semibold text-[#5A3E35]">${p.name}</p><p class="text-[#D9A77A]">$${p.price}</p><button class="text-xs text-[#D9A77A] font-medium mt-1 view-modal">View details</button></div></div>`).join('');
    document.querySelectorAll('#filteredProductsGrid [data-id]').forEach(el=>el.addEventListener('click',()=>openProductModal(customCatalog.find(p=>p.id==parseInt(el.dataset.id)))));
  }
}

document.querySelectorAll('.bundle-add').forEach(btn=>{
  btn.addEventListener('click',()=>{
    let bundle=JSON.parse(btn.dataset.bundle); 
    bundle.items.forEach(id=>{
      let prod=products.find(p=>p.id===id); 
      if(prod) addToCart(prod,1);
    }); 
    showToast("✨ Bundle added to cart!");
  });
});

const cartDrawer=document.getElementById('cartDrawer'),cartOverlay=document.getElementById('cartOverlay'); 
document.getElementById('cartIconBtn').onclick=()=>{cartDrawer.classList.remove('translate-x-full');cartOverlay.classList.remove('hidden');}; 
function closeCart(){cartDrawer.classList.add('translate-x-full');cartOverlay.classList.add('hidden');} 
document.getElementById('closeCartBtn').onclick=closeCart; 
cartOverlay.onclick=closeCart;

document.getElementById('priceFilter').addEventListener('input',(e)=>{
  document.getElementById('priceValue').innerText=`$${e.target.value}`; 
  renderFilteredGrid();
}); 
document.getElementById('categoryFilter').addEventListener('change',()=>renderFilteredGrid()); 
document.getElementById('searchInput').addEventListener('input',()=>renderFilteredGrid());

document.getElementById('closeModalBtn').onclick=closeModal;

document.getElementById('pearlCollectionBtn').addEventListener('click', (e) => { 
  e.preventDefault(); 
  document.getElementById('categoryFilter').value = 'pearl'; 
  renderFilteredGrid('pearl'); 
  window.scrollTo({ top: document.getElementById('filteredProductsGrid').offsetTop - 100, behavior: 'smooth' }); 
});

// reviews
let selectedRating = 0;
const starsWidget = document.querySelectorAll('.review-star');

function updateStarUI(rating) { 
  starsWidget.forEach((star, idx) => { 
    if (idx < rating) star.className = 'fas fa-star review-star text-[#E6B17E]'; 
    else star.className = 'far fa-star review-star text-gray-400'; 
  }); 
}

starsWidget.forEach(star => { 
  star.addEventListener('click', (e) => { 
    selectedRating = parseInt(star.dataset.value); 
    updateStarUI(selectedRating); 
  }); 
});

document.getElementById('submitReviewBtn').addEventListener('click', () => { 
  const comment = document.getElementById('reviewComment').value.trim(); 
  if (!comment || selectedRating === 0) { 
    alert("Please add a rating and comment."); 
    return; 
  } 
  const reviewDiv = document.createElement('div'); 
  reviewDiv.className = 'bg-[#FEF6F0] p-6 rounded-2xl review-card'; 
  let starsHtml = ''; 
  for(let i=0;i<5;i++) starsHtml += i < selectedRating ? '<i class="fas fa-star"></i>' : '<i class="far fa-star"></i>'; 
  reviewDiv.innerHTML = `<div class="flex items-center gap-1 text-[#E6B17E] mb-2">${starsHtml}</div><p class="italic text-gray-700">“${comment.replace(/</g, '&lt;')}”</p><p class="mt-3 font-semibold text-[#5A3E35]">— You <span class="text-xs text-gray-400">Just now</span></p>`; 
  document.getElementById('reviewsContainer').prepend(reviewDiv); 
  document.getElementById('reviewComment').value = ''; 
  selectedRating = 0; 
  updateStarUI(0); 
  showToast("Thank you for your review!"); 
});

window.onload=()=>{ 
  let stored=localStorage.getItem('femmoraCart'); 
  if(stored) cart=JSON.parse(stored); 
  updateCartUI(); 
  renderNewArrivals(); 
  // renderBestSellerSlider(); -- disabled so manual best-seller HTML styling survives refresh
  renderFilteredGrid(); 
  attachProductCardEvents(); 
};