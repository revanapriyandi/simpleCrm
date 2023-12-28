<!---->

<div align="center">
    <h1>SIMPLECRM</h1>
    <h3>◦ Developed with the software and tools below.</h3>
</div>

<p align="center">
  <a href="https://skillicons.dev">
    <img src=https://skillicons.dev/icons?i=alpinejs,css,js,php,vite,git,github />
  </a>
</p>

## 🚀 Getting Started

- ℹ️  PHP ^8.2`

### 🔧 Installation

1. Clone the simpleCrm repository:
```sh
git clone https://github.com/revanapriyandi/simpleCrm
```

2. Change to the project directory:
```sh
cd simpleCrm
```

3. Install the dependencies:
```sh
composer install
```

### 🤖 Running simpleCrm

```sh
php main.php
```

---


## 📂 Repository Structure

```sh
└── simpleCrm/
    ├── .env.example
    ├── .github/
    │   └── workflows/
    │       └── laravel.yml
    ├── .gitpod.yml
    ├── .styleci.yml
    ├── app/
    │   ├── Console/
    │   │   ├── Commands/
    │   │   └── Kernel.php
    │   ├── Enums/
    │   │   └── OrderStatus.php
    │   ├── Exceptions/
    │   │   └── Handler.php
    │   ├── Filament/
    │   │   ├── App/
    │   │   ├── Pages/
    │   │   ├── Resources/
    │   │   └── Widgets/
    │   ├── Forms/
    │   │   └── Components/
    │   ├── Http/
    │   │   ├── Controllers/
    │   │   ├── Kernel.php
    │   │   └── Middleware/
    │   ├── Livewire/
    │   │   ├── Form.php
    │   │   └── Notifications.php
    │   ├── Models/
    │   │   ├── Client.php
    │   │   ├── Fitur.php
    │   │   ├── FiturKerjaSama.php
    │   │   ├── KerjaSama.php
    │   │   ├── LampiranClient.php
    │   │   ├── Produk.php
    │   │   ├── ProdukKerjaSama.php
    │   │   └── User.php
    │   └── Providers/
    │       ├── AppServiceProvider.php
    │       ├── AuthServiceProvider.php
    │       ├── BroadcastServiceProvider.php
    │       ├── EventServiceProvider.php
    │       ├── Filament/
    │       └── RouteServiceProvider.php
    ├── artisan
    ├── bootstrap/
    │   ├── app.php
    │   └── cache/
    ├── composer-local.json
    ├── composer.json
    ├── composer.lock
    ├── config/
    │   ├── app.php
    │   ├── auth.php
    │   ├── blade-icons.php
    │   ├── broadcasting.php
    │   ├── cache.php
    │   ├── cors.php
    │   ├── database.php
    │   ├── debugbar.php
    │   ├── filament.php
    │   ├── filesystems.php
    │   ├── hashing.php
    │   ├── logging.php
    │   ├── mail.php
    │   ├── queue.php
    │   ├── sanctum.php
    │   ├── services.php
    │   ├── session.php
    │   └── view.php
    ├── database/
    │   ├── factories/
    │   │   └── UserFactory.php
    │   ├── migrations/
    │   │   ├── 2014_10_12_000000_create_users_table.php
    │   │   ├── 2014_10_12_100000_create_password_reset_tokens_table.php
    │   │   ├── 2019_08_19_000000_create_failed_jobs_table.php
    │   │   ├── 2019_12_14_000001_create_personal_access_tokens_table.php
    │   │   ├── 2021_12_13_055514_create_media_table.php
    │   │   ├── 2023_12_24_000002_create_produks_table.php
    │   │   ├── 2023_12_24_095857_create_cliens_table.php
    │   │   ├── 2023_12_24_095958_create_lampiran_clients_table.php
    │   │   ├── 2023_12_24_100316_create_menu_kerja_samas_table.php
    │   │   ├── 2023_12_24_100403_create_produk_kerja_samas_table.php
    │   │   ├── 2023_12_24_143659_create_notifications_table.php
    │   │   ├── 2023_12_27_123044_create_fiturs_table.php
    │   │   ├── 2023_12_27_202024_add_product_id_to_kerja_samas_table.php
    │   │   └── 2023_12_27_213815_create_fitur_kerja_samas_table.php
    │   └── seeders/
    │       └── DatabaseSeeder.php
    ├── package-lock.json
    ├── package.json
    ├── phpstan.neon
    ├── pint.json
    ├── postcss.config.js
    ├── public/
    │   ├── .htaccess
    │   ├── css/
    │   │   ├── filament/
    │   │   └── ysfkaya/
    │   ├── index.php
    │   ├── js/
    │   │   ├── filament/
    │   │   └── ysfkaya/
    │   ├── mix-manifest.json
    │   ├── robots.txt
    │   └── web.config
    ├── resources/
    │   ├── css/
    │   │   └── app.css
    │   ├── js/
    │   │   └── app.js
    │   ├── lang/
    │   │   └── en/
    │   ├── svg/
    │   └── views/
    │       ├── components/
    │       ├── livewire/
    │       ├── maintenance.blade.php
    │       └── vendor/
    ├── routes/
    │   ├── api.php
    │   ├── channels.php
    │   ├── console.php
    │   └── web.php
    ├── server.php
    ├── storage/
    │   ├── app/
    │   ├── debugbar/
    │   ├── framework/
    │   │   ├── cache/
    │   │   ├── sessions/
    │   │   └── views/
    │   └── logs/
    ├── tailwind.config.js
    └── vite.config.js

```

---


## 🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github.com/revanapriyandi/simpleCrm/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/revanapriyandi/simpleCrm/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github.com/revanapriyandi/simpleCrm/issues)**: Submit bugs found or log feature requests for REVANAPRIYANDI.

#### *Contributing Guidelines*

<details closed>
<summary>Click to expand</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone <your-forked-repo-url>
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear and concise message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

</details>

---

## 📄 License


This project is protected under the [SELECT-A-LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

## 👏 Acknowledgments

- List any resources, contributors, inspiration, etc. here.

[**Return**](#Top)

---
