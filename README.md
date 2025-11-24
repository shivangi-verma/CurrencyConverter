# 🌍 Convert Currencies in Seconds — No More Guessing Rates!

Ever found yourself Googling *“usd to inr today?”* or stuck calculating conversion rates manually?  
This React Currency Converter lets you swap, convert, and get **real-time exchange rates instantly** with a clean, minimal UI.

🔗 **Live Demo:** https://convertyourcurrencies.netlify.app/

---

## 🚀 Features

- 🔄 **Real-time Conversion** using live currency API  
- 🔁 **Swap Functionality** — instantly flip "From" and "To"  
- 🧩 **Reusable Components** (`InputBox`, custom hook)  
- 🎨 **Tailwind CSS UI** for smooth and responsive design  
- ⚡ **Lightweight & Fast** — no unnecessary dependencies  

---

## 🧠 How It Works

### 1. **Custom Hook: `useCurrencyInfo`**
Fetches up-to-date exchange rates using:
https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/usd.json


Returns an object containing exchange values for all currencies.

---

### 2. **`InputBox` Component**
Reusable component that handles:
- Amount input  
- Currency dropdown  
- Disabled states for readonly fields  

---

### 3. **Swap + Convert Logic**
- **Swap** swaps `from` and `to` currencies effortlessly  
- **Convert** multiplies entered amount with the selected currency rate  

---

## 🛠️ Technologies Used

- **React**
- **Tailwind CSS**
- **JavaScript**
- **Currency API** by *@fawazahmed0*

---

## ▶️ Running the Project

```bash
npm install
npm run dev

