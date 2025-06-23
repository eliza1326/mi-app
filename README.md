# mi-app
HTML

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfumería Handeli - Fragancias de Autor</title>
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <nav class="navbar navbar-expand-md navbar-dark bg-dark fixed-top">
            <div class="container">
                <a class="navbar-brand" href="#">Perfumería Handeli</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item"><a class="nav-link" href="#nuestros-perfumes">Nuestros Perfumes</a></li>
                        <li class="nav-item"><a class="nav-link" href="#promociones">Promociones</a></li>
                        <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <main>
        <section class="hero d-flex justify-content-center align-items-center text-center text-white">
            <div class="container">
                <h1 class="display-4">Donde cada fragancia cuenta una historia</h1>
                <p class="lead my-4">Perfumería de autor, con esencias europeas y árabes de la más alta calidad.</p>
                <a href="#contacto" class="btn btn-primary btn-lg">Realiza tu Pedido</a>
            </div>
        </section>

        <section id="nuestros-perfumes" class="container my-5">
            <h2 class="text-center mb-5">Nuestra Propuesta de Valor</h2>
            <div class="row text-center">
                <div class="col-lg-4 col-md-6 mb-4">
                    <div class="card h-100">
                        <div class="card-body">
                            <i class="bi bi-gem animated-icon"></i>
                            <h3 class="card-title mt-3">Perfumes de la Casa</h3>
                            <p class="card-text">Más de 60 esencias exclusivas. Elige tu fragancia y presentación: envase estándar, recarga o réplica premium.</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 mb-4">
                    <div class="card h-100">
                        <div class="card-body">
                            <i class="bi bi-recycle animated-icon"></i>
                            <h3 class="card-title mt-3">Sistema de Recarga</h3>
                            <p class="card-text">Fomentamos la sostenibilidad. Trae tu envase Handeli y obtén un descuento especial en tu recarga.</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-12 mb-4">
                    <div class="card h-100">
                        <div class="card-body">
                            <i class="bi bi-truck animated-icon"></i>
                            <h3 class="card-title mt-3">Envíos a Nivel Nacional</h3>
                            <p class="card-text">Llegamos a todo el Ecuador a través de Servientrega. Tu fragancia favorita, en la puerta de tu casa.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="promociones" class="bg-light py-5">
            <div class="container text-center">
                <h2 class="mb-4">Obsequios por Compra</h2>
                <button class="btn btn-primary" type="button" data-bs-toggle="collapse" data-bs-target="#detallePromociones">
                    Ver Detalles de los Obsequios
                </button>
                <div class="collapse mt-3" id="detallePromociones">
                    <div class="card card-body mx-auto" style="max-width: 600px;">
                        <p class="mb-2"><strong>Por la compra de un perfume de 100ml:</strong> recibe una crema hidratante del mismo aroma sin costo.</p>
                        <hr>
                        <p class="mb-0"><strong>Por la compra de un perfume de 50ml:</strong> recibe un elegante portaperfumero de viaje.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="contacto" class="container my-5">
            <h2 class="text-center mb-4">Contáctanos</h2>
            <div class="row justify-content-center">
                <div class="col-md-8">
                    <form class="p-4 border rounded-3">
                        <div class="mb-3">
                            <label for="nombre" class="form-label">Nombre Completo</label>
                            <input type="text" class="form-control" id="nombre" required>
                        </div>
                        <div class="mb-3">
                            <label for="email" class="form-label">Correo Electrónico</label>
                            <input type="email" class="form-control" id="email" required>
                        </div>
                        <div class="mb-3">
                            <label for="mensaje" class="form-label">Mensaje o Pedido</label>
                            <textarea class="form-control" id="mensaje" rows="5" placeholder="Indícanos la fragancia y el tamaño que te interesa..."></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary w-100">Enviar</button>
                    </form>
                </div>
            </div>
        </section>
    </main>

    <footer class="footer py-4 bg-dark text-white text-center">
        <div class="container">
            <p class="mb-0">&copy; 2025 Perfumería Handeli. Quito, Ecuador.</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
