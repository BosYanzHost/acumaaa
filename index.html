
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Login</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11"></script>
  <style>
    * {
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      margin: 0;
      padding: 0;
      background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=1920&q=80') no-repeat center center fixed;
      background-size: cover;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .login-container {
      background: rgba(255, 255, 255, 0.12);
      backdrop-filter: blur(15px);
      -webkit-backdrop-filter: blur(15px);
      border-radius: 16px;
      padding: 40px 30px;
      width: 340px;
      box-shadow: 0 8px 24px rgba(0, 0, 0, 0.25);
      border: 1px solid rgba(255, 255, 255, 0.2);
    }

    .login-container h2 {
      text-align: center;
      margin-bottom: 28px;
      color: #fff;
      font-weight: 600;
      font-size: 22px;
    }

    input[type="text"],
    input[type="password"] {
      width: 100%;
      padding: 12px 14px;
      margin-bottom: 18px;
      border-radius: 10px;
      border: none;
      background: rgba(255, 255, 255, 0.3);
      font-size: 14px;
      color: #fff;
    }

.password-wrapper {
  position: relative;
}

.password-wrapper input {
  width: 100%;
  padding-right: 44px; /* Tambah space kanan untuk icon */
  padding-left: 14px;
  height: 42px; /* buat tinggi input tetap sama */
  border-radius: 10px;
  border: none;
  background: rgba(255, 255, 255, 0.3);
  font-size: 14px;
  color: #fff;
  box-sizing: border-box;
}

.toggle-password {
  position: absolute;
  top: 38%; /* dari 50% ke 48% supaya agak naik */
  right: 12px;
  transform: translateY(-50%);
  cursor: pointer;
  color: #eee;
  width: 24px;
  height: 24px;
  fill: #eee;
  user-select: none;
}


    input::placeholder {
      color: #eee;
    }

    input:focus {
      outline: none;
      border: 1px solid #d6b8ff;
      background: rgba(255, 255, 255, 0.4);
    }

    button {
      width: 100%;
      padding: 12px;
      font-size: 15px;
      font-weight: 600;
      border: none;
      border-radius: 10px;
      background: linear-gradient(to right, #a18cd1, #fbc2eb);
      color: #fff;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background: linear-gradient(to right, #a18cd1, #e2b5e8);
    }
  </style>
</head>
<body>
  <div class="login-container">
    <h2>Login</h2>
    <form id="loginForm" autocomplete="off">
      <input type="text" id="username" placeholder="Username" required />
<div class="password-wrapper">
  <input type="password" id="password" placeholder="Password" required />
  <svg id="togglePassword" class="toggle-password" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" focusable="false">
    <path d="M12 5c-7 0-11 7-11 7s4 7 11 7 11-7 11-7-4-7-11-7zm0 12a5 5 0 110-10 5 5 0 010 10zm0-8a3 3 0 100 6 3 3 0 000-6z"/>
  </svg>
</div>

      <button type="submit">Masuk</button>
    </form>
  </div>

  <script>
    const correctUsername = "Yanz";
    const correctPassword = "0011";
    const redirectURL = "resapi.html";

    const togglePassword = document.getElementById("togglePassword");
    const passwordInput = document.getElementById("password");

    // SVG paths for icon states:
    const eyeOpen = "M12 5c-7 0-11 7-11 7s4 7 11 7 11-7 11-7-4-7-11-7zm0 12a5 5 0 110-10 5 5 0 010 10zm0-8a3 3 0 100 6 3 3 0 000-6z";
    const eyeClosed = "M2.293 2.293a1 1 0 011.414 0L21.707 20.293a1 1 0 01-1.414 1.414l-3.184-3.184A9.953 9.953 0 0112 19c-7 0-11-7-11-7a16.78 16.78 0 014.022-5.691L2.293 2.293zm5.252 5.252a3 3 0 104.242 4.242l-4.242-4.242zM12 5c.89 0 1.738.177 2.5.493l-1.758 1.758a3 3 0 00-2.245-2.245L12 5zm9.707 9.707a16.77 16.77 0 01-4.91 3.701l-1.592-1.592a5 5 0 00-6.864-6.864l-1.59-1.59A16.78 16.78 0 0121 12c0 .634-.065 1.254-.293 1.707z";

    togglePassword.addEventListener("click", () => {
      if (passwordInput.type === "password") {
        passwordInput.type = "text";
        // Ganti icon jadi mata coret (tertutup)
        togglePassword.querySelector("path").setAttribute("d", eyeClosed);
      } else {
        passwordInput.type = "password";
        // Ganti icon jadi mata terbuka
        togglePassword.querySelector("path").setAttribute("d", eyeOpen);
      }
    });

    document.getElementById("loginForm").addEventListener("submit", function (e) {
      e.preventDefault();
      const username = document.getElementById("username").value.trim();
      const password = passwordInput.value.trim();

      if (username === correctUsername && password === correctPassword) {
        Swal.fire({
          toast: true,
          position: 'top-end',
          icon: 'success',
          title: 'Login berhasil!',
          showConfirmButton: false,
          timer: 1500
        }).then(() => {
          window.location.href = redirectURL;
        });
      } else {
        Swal.fire({
          toast: true,
          position: 'top-end',
          icon: 'error',
          title: 'Username atau Password salah!',
          showConfirmButton: false,
          timer: 2000
        });
      }
    });
  </script>
</body>
</html>
