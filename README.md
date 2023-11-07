# Vercel PHP Info

This repository hosts a minimal PHP application with a `phpinfo()` page, ready to be deployed on Vercel's free tier. The main function of this application is to provide useful information about the Vercel environment for PHP programmers using this platform. Moreover, it serves as a simple and practical example of how to run PHP code on Vercel, functioning as a kind of boilerplate for PHP projects.

## Demo

A live demo can be found at: [https://phpinfo.vercel.app/](https://phpinfo.vercel.app/)

## How to Use

1. Click the button below to clone this repository and deploy it on Vercel:

   [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fvolneifilho%2Fvercel-phpinfo)

2. Or clone the repository manually and deploy it with the Vercel CLI:

   ```bash
   git clone https://github.com/volneifilho/vercel-phpinfo.git
   cd vercel-phpinfo
   vercel
   ```
## Project Structure

This project consists of two main files:

- `/api/phpinfo.php`: This file contains a simple PHP script that calls the `phpinfo()` function, generating a page with information about the PHP configuration in the Vercel environment.
- `vercel.json`: This configuration file directs Vercel on how to handle requests and execute PHP files in this project.

## Contributing

Feel free to clone, modify, and reuse this project. If you encounter any issues or have any improvements, feel free to open an Issue or a Pull Request.

## License

[MIT](LICENSE)
