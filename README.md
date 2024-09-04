<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bienvenido a esta monda</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div id="auth-forms">
            <div id="login-form">
                <h2>Iniciar sesión</h2>
                <form>
                    <label for="login-email">Correo:</label>
                    <input type="email" id="login-email" required>
                    <label for="login-password">Contraseña:</label>
                    <input type="password" id="login-password" required>
                    <button type="button" onclick="login()">Iniciar sesión</button>
                    <p>¿No tienes cuenta? <a href="#" onclick="showRegister()">Regístrate aquí</a></p>
                </form>
            </div>

            <div id="register-form" style="display:none;">
                <h2>Registrarse</h2>
                <form>
                    <label for="register-email">Correo:</label>
                    <input type="email" id="register-email" required>
                    <label for="register-password">Contraseña:</label>
                    <input type="password" id="register-password" required>
                    <button type="button" onclick="register()">Registrarse</button>
                    <p>¿Ya tienes cuenta? <a href="#" onclick="showLogin()">Inicia sesión aquí</a></p>
                </form>
            </div>
        </div>

        <div id="welcome-message" style="display:none;">
            <h2>¡Bienvenidos a esta monda!</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/36/Nicolas_Maduro_2013.jpg/800px-Nicolas_Maduro_2013.jpg" alt="Nicolás Maduro">
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
