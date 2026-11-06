# Melinoe Luna

### Mujer dev en Go · Backend & DevOps

Construyo APIs pequeñas, CLIs y despliegues que se pueden explicar, medir y repetir. Go es mi lenguaje principal; Rust, Docker, Linux y Cloudflare completan la caja de herramientas.

- **Portfolio:** [melinoeluna4.github.io](https://melinoeluna4.github.io/)
- **Blog:** [melinoeluna4.github.io/blog](https://melinoeluna4.github.io/blog/)
- **LinkedIn:** [melinoeluna4](https://www.linkedin.com/in/melinoeluna4)
- **X:** [@melinoeluna4](https://x.com/melinoeluna4)

## Herramientas que estoy publicando

| CLI | Qué resuelve |
| --- | --- |
| [envcheck](https://github.com/melinoeluna4/envcheck) | Compara `.env` con `.env.example` y falla antes de que el servicio arranque. |
| [portwait](https://github.com/melinoeluna4/portwait) | Espera a que los puertos TCP estén listos, sin `sleep` frágiles en CI. |
| [httpcheck](https://github.com/melinoeluna4/httpcheck) | Smoke tests HTTP con reintentos, timeout y código esperado. |
| [treehash](https://github.com/melinoeluna4/treehash) | Hash determinista de un árbol de directorios para cache keys de CI. |

Las cuatro son Go estándar, sin dependencias externas, con tests y CI.

## Ahora

- Publicando una colección de CLIs pequeñas en Go, con tests, CI y README.
- Profundizando en observabilidad, Kubernetes y despliegues reproducibles.
- Escribiendo notas técnicas en el [blog](https://melinoeluna4.github.io/blog/).

## Stack

`Go` · `Rust` · `Docker` · `Linux` · `GitHub Actions` · `Cloudflare` · `SQL` · `Astro` · `TypeScript`

## Una muestra

```text
$ envcheck
envcheck: .env against .env.example
missing (1): DATABASE_URL
FAIL
```

```text
$ portwait localhost:5432
waiting for 1 endpoint(s), timeout 30s
  localhost:5432 ready (8ms)
all endpoints ready in 8ms
```

## Principios

- Menos superficie, menos fallos.
- Si no se puede medir, no está terminado.
- La documentación es parte del sistema.
- Automatiza lo que repites dos veces.

---

Hecho con Go, tests y GitHub Actions. Portfolio: [melinoeluna4.github.io](https://melinoeluna4.github.io/)
