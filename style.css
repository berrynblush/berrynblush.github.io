const products = [
  {
    name: "Gold Necklace",
    price: "₹12,000",
    image: "https://via.placeholder.com/200x200?text=Necklace"
  },
  {
    name: "Diamond Ring",
    price: "₹20,000",
    image: "https://via.placeholder.com/200x200?text=Ring"
  },
  {
    name: "Pearl Earrings",
    price: "₹7,500",
    image: "https://via.placeholder.com/200x200?text=Earrings"
  }
];

const productList = document.getElementById("product-list");

products.forEach(product => {
  const card = document.createElement("div");
  card.className = "product-card";
  card.innerHTML = `
    <img src="${product.image}" alt="${product.name}">
    <h3>${product.name}</h3>
    <p>${product.price}</p>
    <button>Add to Cart</button>
  `;
  productList.appendChild(card);
});
