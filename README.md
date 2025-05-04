# Mada Rent

> A centralized rental listings platform for Madagascar

## What is Mada Rent?

Mada Rent is a web application designed to simplify the process of finding and listing rental properties across Madagascar. By aggregating scattered Facebook Group posts and offering direct property-owner listings, it provides a single, reliable source for renters and landlords alike.

## What does it do?

- **Centralized Listings**  
  Pulls recent rental posts from multiple Facebook groups into one unified feed.

- **Owner Direct Posts**  
  Allows “propriétaires” (landlords) to create and manage their own listings, with clear availability statuses (available, booked, rented).

- **Advanced Filters**  
  Search by city, price range, property type, and more to quickly find the right home.

- **Verified Quality**  
  All listings—whether aggregated or owner-submitted—are manually reviewed to ensure accuracy and reduce scams.

- **Secure Contact Gateway**  
  Renters pay a small fee (5 000 Ar) to contact landlords directly; landlords pay (10 000 Ar) per confirmed visit, ensuring serious inquiries only.

## Built With

- **Frontend:**  
  [SvelteKit](https://kit.svelte.dev/) – fast, reactive UI framework  
  [PocketBase](https://pocketbase.io/) – self-hosted backend for authentication and data storage  

- **Backend Aggregation Service:**  
  [Go](https://golang.org/) + [Fiber](https://gofiber.io/) – high-performance microservice to pull and normalize Facebook Group data  

- **Deployment & Hosting:**  
  [Coolify](https://coolify.io/) on a Hetzner VPS – containerized deployment with automatic builds and reverse-proxy routing  

---

## License

This codebase is proprietary and closed source. See the [LICENSE](./license) for details.

## Contact

Ohayo Dev and Design  
📧 axeldiaryrakotoarivao@gmail.com  
