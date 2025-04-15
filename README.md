# 🇹🇿 Tanzania Universities - PHP Package

This package provides a list of all recognized universities in Tanzania. It's designed for developers who need university data for educational apps, forms, dropdowns, APIs, or any academic-related platforms.

---

## 📦 Installation

You can install the package via Composer:

```bash
composer require salymdev/tanzania-universities

🚀 Usage

require 'vendor/autoload.php';

use SalymMbise\Universities\UniversityList;

$universities = UniversityList::all();

foreach ($universities as $uni) {
    echo $uni['name'] . " - " . $uni['location'] . "\n";
}

Each university includes:

name (e.g. University of Dar es Salaam)

abbreviation (e.g. UDSM)

type (e.g. Public, Private)

location (e.g. Dar es Salaam)

website (e.g. https://www.udsm.ac.tz)

📚 Example Output

[
    [
        'name' => 'University of Dar es Salaam',
        'abbreviation' => 'UDSM',
        'type' => 'Public',
        'location' => 'Dar es Salaam',
        'website' => 'https://www.udsm.ac.tz'
    ],
    ...
]


🤝 Contributing
Feel free to fork the repo, improve the data or structure, and send a pull request. Let’s make this more useful together!

📧 Author
Salym Mbise
📩 salymdev@gmail.com
🐙 github.com/salymdev


📝 License
Licensed under the MIT License.


---

you can tweak the emojis or sections if you want it more minimal — but this version will look pro on GitHub and Packagist 😎


