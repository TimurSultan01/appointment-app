# Terminplaner (React + Laravel)

Ein einfacher Terminplaner ähnlich wie Doodle, umgesetzt mit React (TypeScript) im Frontend und Laravel im Backend.

---

## Voraussetzungen
  
- Node.js (LTS-Version, z.B. ≥ 18)
- PHP (≥ 8.1)  
- Composer  
- MySQL Server    
- Postman (optional, zum Testen der API)

---

## Installation

### 1. Repository klonen

```bash
git clone https://github.com/TimurSultan01/appointment-app.git
cd terminplaner
```

### 2. Frontend installieren und starten

```bash
cd frontend
npm install
npm start
```

- Das Frontend läuft danach unter `http://localhost:3000`

### 3. Backend installieren und starten

```bash
cd ../backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

- Das Backend läuft danach unter `http://localhost:8000`.

---

## Nützliche VS Code Extensions

### Frontend (React/TypeScript)

- ESLint  
- Prettier  
- Tailwind CSS IntelliSense  
- TypeScript Hero  
- React Snippets  

### Backend (Laravel/PHP)

- PHP Intelephense  
- Laravel Extra Intellisense  
- Laravel Blade Snippets  
- Laravel Artisan  
- DotENV  
