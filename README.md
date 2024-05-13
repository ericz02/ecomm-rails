**Ecomm/EMart Project README**

---

### Project Overview

Welcome to my Ecomm project! This project is built using Ruby on Rails 7 along with several modern technologies to provide a seamless and efficient Ecomm experience. Below you'll find information on how to set up and run the project locally, as well as an overview of the technologies used.

<div>
    <a href="https://www.loom.com/share/3743168c63de4dcaa2b79efd3b08935b">
      <p>EricMart - 12 May 2024 - Watch Video</p>
    </a>
    <a href="https://www.loom.com/share/3743168c63de4dcaa2b79efd3b08935b">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/3743168c63de4dcaa2b79efd3b08935b-with-play.gif">
    </a>
</div>
  
## Tech Stack

- [Ruby on Rails 7](https://rubyonrails.org/) - A web application framework written in Ruby.
- [Hotwire](https://hotwired.dev/) - A set of tools for building modern web applications without using much JavaScript.
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework for building custom designs.
- [Stripe](https://stripe.com/) - A payment processing platform for online businesses.
- [PostgreSQL](https://www.postgresql.org/) - A powerful, open-source object-relational database system.

## Gems Used

- [pg](https://rubygems.org/gems/pg) - PostgreSQL adapter for Ruby.
- [puma](https://rubygems.org/gems/puma) - A simple, fast, threaded, and highly concurrent HTTP 1.1 server for Ruby/Rack applications.
- [importmap-rails](https://rubygems.org/gems/importmap-rails) - A library for managing JavaScript dependencies using ESM import maps.
- [turbo-rails](https://rubygems.org/gems/turbo-rails) - Hotwire's SPA-like page accelerator for Rails applications.
- [stimulus-rails](https://rubygems.org/gems/stimulus-rails) - Hotwire's modest JavaScript framework for Rails applications.
- [tailwindcss-rails](https://rubygems.org/gems/tailwindcss-rails) - Integrates Tailwind CSS with Rails applications.
- [devise](https://rubygems.org/gems/devise) - Flexible authentication solution for Rails applications.
- [font-awesome-sass](https://rubygems.org/gems/font-awesome-sass) - Font Awesome 5.0.13 Sass gem for Rails projects.
- [stripe](https://rubygems.org/gems/stripe) - Ruby library for the Stripe API.
- [pagy](https://rubygems.org/gems/pagy) - A fast and light pagination gem for Ruby web frameworks.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ericz02/ericmart-rails
   ```

2. Install dependencies:

   ```bash
   bundle install
   ```

3. Set up the database:

   ```bash
   rails db:setup
   ```

4. Start the Rails server:

   ```bash
   rails server
   ```

5. Open your browser and navigate to `http://localhost:3000` to view the application as a customer..
   Open your browser and navigate to `http://localhost:3000/admin` to view the application as a seller.

## Contributing

Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://opensource.org/licenses/MIT)
