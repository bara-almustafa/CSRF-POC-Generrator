# CSRF POC Generator

A simple and powerful client-side tool to generate Cross-Site Request Forgery (CSRF) Proof-of-Concept (PoC) attack pages. Built purely with HTML, CSS, and JavaScript, this tool helps security professionals and researchers quickly create custom CSRF demos without backend dependencies.

## Features

- Specify target URL and HTTP method (POST/GET)
- Customize form parameters and CSRF token name/value
- Simulate cookies for session handling
- Generate ready-to-use, auto-submitting HTML exploit pages
- Fully client-side, no server required
- Easy to use for vulnerability testing and security education

## Demo

Open the `index.html` file in any modern browser to start generating CSRF POCs instantly.

## Usage

1. Enter the target URL vulnerable to CSRF.
2. Select the HTTP method (POST or GET).
3. Add form parameters (key=value pairs, one per line).
4. Specify the CSRF token name and value if applicable.
5. Optionally, add a cookie string to simulate session cookies.
6. Click "Generate CSRF POC" to output the malicious HTML.
7. Copy the generated HTML and save it as a standalone file to test the vulnerability.

## Why Use This Tool?

Cross-Site Request Forgery is a critical web security vulnerability that can lead to unwanted or malicious actions performed on behalf of authenticated users. This open-source generator simplifies creating PoCs for security assessments and demonstrations.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repo and submit pull requests.

## License

This project is licensed under the MIT License.

## Contact

Created by Bara Almustafa  
GitHub: [bara-almustafa](https://github.com/bara-almustafa)  
Project URL: https://github.com/bara-almustafa/CSRF-POC-Generrator

---

Happy testing and stay secure!
