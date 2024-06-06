# Movie-Series-Api

This project provides a Flask-based API to fetch Bollywood, Hollywood movies, and web series details along with their images.

## Features

- Fetch Bollywood movies details with images
- Fetch Hollywood movies details with images
- Fetch web series details with images

## Endpoints

- `/bollywood` - Fetch Bollywood movies details
- `/hollywood` - Fetch Hollywood movies details
- `/webseries` - Fetch web series details
- `/webseries2` - Fetch web series details if /webseries doesnt worked.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/TraxDinosaur/Movie-Series-Api.git
cd Movie-Series-Api
```

2. Create a virtual environment and activate it:

```bash
python -m venv venv
source venv/bin/activate # On Windows use `venv\Scripts\activate`
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

4. Run the application:

```bash
flask run
```

The API will be available at `http://127.0.0.1:5000`.

## Usage

### Bollywood Movies

Fetch details of new Bollywood movies:

```sh
GET /bollywood
```

### Hollywood Movies

Fetch details of new Hollywood movies:

```sh
GET /hollywood
```

### Web Series

Fetch details of new web series:

```sh
GET /webseries
GET /webseries2
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License

This project is licensed under the CC BY-SA 4.0 License. See the [LICENSE](LICENSE) file for details.

## Contact

Created by [@TraxDinosaur](https://github.com/TraxDinosaur) - feel free to contact me!

---

Made with ❤️ by [TraxDinosaur](https://github.com/TraxDinosaur)
