- 👋 Hi, I’m @NIPEREG
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
NIPEREG/NIPEREG is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>

<html>

<head>

  <title>Tabuleiro de Roleta</title>

  <style>

    /* Estilos CSS para o tabuleiro de roleta */

    .roleta {

      display: flex;

      flex-wrap: wrap;

      width: 600px;

      height: 600px;

    }

    

    .roleta .slot {

      width: 100px;

      height: 100px;

      border: 1px solid #000;

      box-sizing: border-box;

      display: flex;

      align-items: center;

      justify-content: center;

      font-size: 20px;

      font-weight: bold;

    }

  </style>

</head>

<body>

  <div class="roleta"></div>

  <script>

    // Código JavaScript para gerar o tabuleiro de roleta

    const roletaDiv = document.querySelector('.roleta');

    const numeros = ['0', '32', '15', '19', '4', '21', '2', '25', '17', '34', '6', '27', '13', '36', '11', '30', '8', '23', '10', '5', '24', '16', '33', '1', '20', '14', '31', '9', '22', '18', '29', '7', '28', '12', '35', '3', '26'];

    numeros.forEach(numero => {

      const slot = document.createElement('div');

      slot.classList.add('slot');

      slot.textContent = numero;

      roletaDiv.appendChild(slot);

    });

  </script>

</body>

</html>

