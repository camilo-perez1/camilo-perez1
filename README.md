<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
</head>
<body>
    <div class="page">
        <header class="header">
            <h1 class="repo-title">¡Bienvenido a mi perfil!</h1>
            <div class="header-meta">
                <span>Soy <strong>Camilo Perez</strong>, desarrollador apasionado por C# </span>
            </div>
    </header>
    <main class="content-grid">
            <section class="left">
                <div class="welcome-card">
                    <p>
                        Soy <strong>Camilo Perez</strong>, un desarrollador apasionado por la tecnología y la innovación.
                        Aquí comparto mis proyectos, ejemplos de código y herramientas que uso en mis trabajos académicos y personales.
                    </p>
                    <div class="lang-box">
                        <h3>Most Used Languages</h3>
                        <ul class="lang-list">
                            <li>C# — 82.24%</li>
                            <li>HTML — 6.2%</li>
                            <li>TS/SQL — 5.5%</li>
                        </ul>
                    </div>
                    <div class="socials">
                        <h3>Mis redes sociales</h3>
                        <div class="social-row">
                            <div class="social-card">
                                <div class="social-title">GitHub</div>
                                <div class="social-body">
                                    <a href="https://github.com/camilo-perez1" target="_blank">github.com/camilo-perez1</a>
                                    <small>Repositorios · Contribuciones</small>
                                </div>
                            </div>
                            <div class="social-card">
                                <div class="social-title">Correo</div>
                                <div class="social-body">
                                    <span>abccamilo15@gmail.com</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="projects">
                        <h3>Mis Proyectos</h3>
                        <div class="project-row">
                            <div class="project-pill"><a href="#" target="_blank">Farmacia Mía</a></div>
                        </div>
                    </div>
                </div>
            </section>
            <aside class="right">
                <div class="logo-image-card">
                    <img src="https://tse3.mm.bing.net/th/id/OIP.KuhDJrQLa7FO0ntYef0W9gHaEc?rs=1&pid=ImgDetMain&o=7&rm=3.png" alt="Logo C#" class="logo-img" />
                </div>
                <div class="mini-info">
                    <p><strong>Camilo Perez</strong></p>
                    <p class="muted">Desarrollador · Estudiante</p>
                    <p class="meta-links">
                        <a href="mailto:abccamilo15@gmail.com">abccamilo15@gmail.com</a><br>
                        <a href="https://github.com/camilo-perez1" target="_blank">github.com/camilo-perez1</a>
                    </p>
                </div>
            </aside>
        </main>
        <footer class="footer">
            <div>© 2025 Camilo Perez</div>
        </footer>
    </div>
    <style>
        body {
            margin: 0;
            padding: 24px;
            font-family: Arial, Helvetica, sans-serif;
            background: #0f1724;
            color: #e6eef6;
        }
        .page {
            max-width: 1100px;
            margin: 0 auto;
        }
        /* Header */
        .header {
            border: 1px solid rgba(255,255,255,0.04);
            padding: 18px;
            border-radius: 8px;
        }
        .repo-title {
            margin: 0;
            font-size: 20px;
            color: #60a5fa;
        }
        .header-meta {
            display: flex;
            justify-content: space-between;
            gap: 12px;
            margin-top: 8px;
            align-items: center;
            color: #9aa4b2;
        }
        /* Layout */
        .content-grid {
            display: grid;
            grid-template-columns: 1fr 300px;
            gap: 18px;
            margin-top: 18px;
        }
        /* Cards */
        .welcome-card,
        .profile-image-card,
        .logo-image-card {
            background: #0b1220;
            padding: 18px;
            border-radius: 8px;
            border: 1px solid rgba(255,255,255,0.03);
        }
        a { color: #60a5fa; text-decoration: none; }
        a:hover { text-decoration: underline; }
        .lang-list,
        .project-row { list-style: none; margin: 8px 0; padding: 0; color: #9aa4b2; }
        .social-row { display: flex; gap: 10px; }
        .social-card { flex: 1; background: #111827; padding: 10px; border-radius: 8px; }
    .profile-img { width: 100%; max-width: 260px; border-radius: 6px; display: block; margin: 0 auto; }
    .logo-img { width: 100%; max-width: 180px; border-radius: 6px; display: block; margin: 0 auto; }
        .footer { margin-top: 16px; text-align: center; color: #9aa4b2; font-size: 0.9rem; }
        @media (max-width: 920px) {
            .content-grid { grid-template-columns: 1fr; }
            .right { order: -1; }
            .profile-img { max-width: 140px; }
            .social-row { flex-direction: column; }
        }
    </style>
</body>
</html>

<!---
camilo-perez1/camilo-perez1 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
