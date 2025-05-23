<<<<<<< HEAD
### System Specifications

| Requirements | Versions |
| :----------: | :------: |
|   LARAVEL    |   10.x    |
|     PHP      | ^8.1.10  |
|    MYSQL     |   ^10.4.25   |

## Configuration

1.  Clone this repository.

    ```bash
        $   git clone https://github.com/ericnicdao069/backend-dev-exam.git
    ```

2.  Recreate environment variable file.

    ```bash
        $   cp .env.example .env
    ```

3.  Install composer and npm.

    ```bash
        $   composer install && npm install
    ```

4.  Generate Application Key.

    ```bash
        $   php artisan key:generate
    ```

5.  Create your DB and update your DB configs in .env.

    ```bash
        $   DB_CONNECTION=mysql
        $   DB_HOST=127.0.0.1
        $   DB_PORT=3306
        $   DB_DATABASE=laravel
        $   DB_USERNAME=root
        $   DB_PASSWORD=
    ```

6.  Execute Database Migration and Seeders.

    ```bash
        $   php artisan migrate --seed
    ```

7.  Create a symlink for Storage in Public Directory.

    ```bash
        $   php artisan storage:link
    ```

8.  Generate Ziggy routes.

    ```bash
        $   php artisan ziggy:generate
    ```

9.  Run local server.

    ```bash
        $   php artisan serve
    ```

10.  Front Build.

    ```bash
        $   npm run dev
        $   npm run build
    ```

---

### Step-by-step:

1. **Delete everything starting from** `<<<<<<< HEAD` **to** `>>>>>>> b5a143a (Initial commit)` — including those lines.
2. Keep only the full Laravel setup as shown above.
3. Save the file.

---

### After fixing the conflict:

Run this in your terminal:

```bash
git add README.md
git rebase --continue
=======
# qa-engineer-exam
This repository contains the files for my QA Engineer exam project. It includes all the necessary components to set up and run the project. Please follow the installation instructions below to get everything up and running on your local machine.
## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/qa-engineer-exam.git
>>>>>>> 76a15d8 (Update README.md)
