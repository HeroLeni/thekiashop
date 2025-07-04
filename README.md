# 🚗 API Tienda Kia

API RESTful para gestionar vehículos, clientes, categorías y pedidos de una tienda Kia. Desarrollado con NestJS, TypeORM y MySQL.

---

API RESTful to manage vehicles, customers, categories, and orders for a Kia dealership. Built with NestJS, TypeORM, and MySQL.

## 📦 Tecnologías / Technologies

- NestJS
- TypeORM
- MySQL
- Insomnia (testing)

## ⚙️ Instalación / Installation

```bash
npm install
npm run start:dev
```

## 🔐 Variables de entorno (.env) / Environment variables

```env
DB_HOST=localhost
DB_PORT=3306
DB_USERNAME=root
DB_PASSWORD=
DB_NAME=tienda_kia
```

## 📮 Endpoints principales / Main Endpoints

| Recurso / Resource | Métodos / Methods      | Ejemplo / Example     |
|--------------------|------------------------|------------------------|
| `/carro`           | GET, POST, PUT, DELETE | `/carro/1`             |
| `/cliente`         | GET, POST, PUT, DELETE | `/cliente/1`           |
| `/categoria`       | GET, POST, PUT, DELETE | `/categoria/1`         |
| `/pedido`          | GET, POST, PUT, DELETE | `/pedido/1`            |

## 📫 Autor / Author

**Juan Eduardo Zorrilla Chavez**  
📧 [juanesgatito13738@gmail.com]
