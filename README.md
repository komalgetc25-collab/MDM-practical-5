<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Food Menu</title>

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-gray-100">

  <!-- Heading -->
  <section class="py-10">

    <h1 class="text-3xl font-bold text-center text-gray-800 mb-8">
      Our Food Menu
    </h1>

    <!-- Grid -->
    <div class="max-w-6xl mx-auto px-5 grid grid-cols-1 md:grid-cols-3 gap-6">

      <!-- Card 1 -->
      <div class="bg-white rounded-lg shadow-md overflow-hidden">

        <img
          src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38"
          alt="Pizza"
          class="w-full h-48 object-cover"
        >

        <div class="p-5">

          <h2 class="text-xl font-bold text-gray-800">
            Pizza
          </h2>

          <p class="text-gray-600 mt-2">
            Delicious cheese pizza with fresh vegetables.
          </p>

          <button class="mt-4 bg-red-500 text-white px-5 py-2 rounded
                         hover:bg-red-600">
            Order Now
          </button>

        </div>
      </div>


      <!-- Card 2 -->
      <div class="bg-white rounded-lg shadow-md overflow-hidden">

        <img
          src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd"
          alt="Burger"
          class="w-full h-48 object-cover"
        >

        <div class="p-5">

          <h2 class="text-xl font-bold text-gray-800">
            Burger
          </h2>

          <p class="text-gray-600 mt-2">
            Juicy burger served with fresh vegetables and cheese.
          </p>

          <button class="mt-4 bg-red-500 text-white px-5 py-2 rounded
                         hover:bg-red-600">
            Order Now
          </button>

        </div>
      </div>


      <!-- Card 3 -->
      <div class="bg-white rounded-lg shadow-md overflow-hidden">

        <img
          src="https://images.unsplash.com/photo-1551024506-0bccd828d307"
          alt="Dessert"
          class="w-full h-48 object-cover"
        >

        <div class="p-5">

          <h2 class="text-xl font-bold text-gray-800">
            Dessert
          </h2>

          <p class="text-gray-600 mt-2">
            Sweet and delicious dessert to finish your meal.
          </p>

          <button class="mt-4 bg-red-500 text-white px-5 py-2 rounded
                         hover:bg-red-600">
            Order Now
          </button>

        </div>
      </div>

    </div>

  </section>

</body>
</html>
