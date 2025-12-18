:root {
    --black: #050505;
    --dark: #121212;
    --blue: #007bff;
    --white: #ffffff;
}

body { font-family: 'Tajawal', sans-serif; background: var(--black); color: var(--white); margin: 0; direction: rtl; }
header { background: var(--dark); padding: 20px; display: flex; justify-content: space-between; border-bottom: 2px solid var(--blue); }
.logo span { color: var(--blue); }
.products-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; padding: 20px; }
.product-card { background: var(--dark); padding: 20px; border-radius: 15px; border: 1px solid #333; text-align: center; }
.btn-buy { background: var(--blue); color: white; border: none; padding: 10px; border-radius: 5px; width: 100%; cursor: pointer; }
.add-box { background: var(--dark); padding: 20px; border-radius: 10px; display: flex; flex-direction: column; gap: 10px; }
input, select { padding: 10px; background: #000; color: #fff; border: 1px solid #444; }
