# Static Gen Rust

This incorporates static files and Tera templates into the binary. It looks for 2 directories: `static` and `templates`. The `static` directory is for static files like images, css, js, etc. The `templates` directory is for Tera templates. This is great for platforms like AWS Lambda and Cloudflare Workers where you can't have a file system in the traditional sense.