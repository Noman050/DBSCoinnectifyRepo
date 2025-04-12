### **GitHub Description** (for repository overview)  
**DBSCoinnectify** is a lightweight crypto-banking web app built with Django and SQLite3. It simulates secure deposits, withdrawals, and transaction tracking with real-time crypto-fiat conversion via CoinGecko API. Features role-based auth, admin dashboard, and Netlify deployment.  

---

### **README.md**  

# DBSCoinnectify  

![DBSCoinnectify Logo](https://via.placeholder.com/150x50?text=DBSCoinnectify)  

A lightweight, user-friendly crypto-banking web application for managing simulated cryptocurrency transactions. Built with Django, SQLite3, and real-time data from CoinGecko API.  

**Live Demo**: [Netlify Deployment](https://dbscoinnectify.netlify.app/)  

---

## ✨ Features  
- **Secure Authentication**: Role-based login (user/admin) with CSRF protection.  
- **Crypto Transactions**: Simulated deposits/withdrawals via TRC20 or BNB Smart Chain.  
- **Real-Time Converter**: Live crypto-to-fiat rates using CoinGecko API.  
- **Transaction History**: Filterable records with balance tracking.  
- **Admin Dashboard**: CRUD operations for users, wallets, and transactions.  
- **Responsive UI**: Clean interface built with Tailwind CSS.  

---

## 🛠️ Technologies  
- **Backend**: Django (Python)  
- **Database**: SQLite3  
- **Frontend**: HTML, JavaScript, Tailwind CSS  
- **API**: CoinGecko (real-time crypto rates)  
- **Security**: Werkzeug hashing, CSRF tokens, input validation  
- **Deployment**: Netlify  

---

## � Setup & Installation  
1. **Clone the repository**:  
   ```bash
   git clone https://github.com/saeed123991/DBSConnectify.git
   cd DBSConnectify
   ```

2. **Install dependencies**:  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run migrations**:  
   ```bash
   python manage.py migrate
   ```

4. **Start the server**:  
   ```bash
   python manage.py runserver
   ```
   Access at `http://localhost:8000`.  

**Admin Credentials**:  
- Email: `admin@admin.com`  
- Password: `admin@123`  

---

## 📸 Screenshots  

### Landing Page  
![Landing Page](https://github.com/user-attachments/assets/86f1b582-7209-4460-ae81-66817faefda1)  
*Clean homepage with registration/login options*  

### Dashboard  
![Dashboard](https://github.com/user-attachments/assets/52eb5dcc-8c5e-4e59-bd90-20782fee6bd3)
*User dashboard showing balances, transaction history, and action buttons*  

### Crypto Converter  
![Converter](https://github.com/user-attachments/assets/3785a51a-fad2-423f-aff6-a84ce9d421a8)
*Real-time conversion tool with dropdown menus for crypto/fiat selection*  

---

## 📄 Documentation  
- **Report**: [DBSCoinnectify_Report.pdf](DBSCoinnectify_Report.pdf)  
- **Flow Diagram**: See `Figure 2` in the report.  

---

## 🔒 Security  
- CSRF protection with Django middleware.  
- Password hashing via Werkzeug.  
- Input sanitization to prevent SQL injection.  

---

## 📜 License  
MIT License. See [LICENSE](LICENSE) for details.  

---

## 🙏 Credits  
- **Lecturer**: Dr. Hamidreza Khaleghzadeh  
- **Developer**: Saeed Anwar (20029527)  
- **API**: [CoinGecko](https://www.coingecko.com/api)  
```
