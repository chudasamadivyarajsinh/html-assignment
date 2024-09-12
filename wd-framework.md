#### (1)Make a card using Tailwind css 
#### ans.
```html
<html>
<head>
    <title>Document</title> 
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body>
    <div class="cards  flex  justify-around  mx-auto mt-24">

    <div class="card h-52 w-60 border rounded-md p-5  flex flex-col justify-around  items-start">
        <h1 class=" font-bold  text-2xl">card title</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
        <a href="#" class="border rounded-md w-24 p-1 bg-blue-600 text-white text-center">know more</a>
    </div>

    <div class="card h-52 w-60 border rounded-md p-5  flex flex-col justify-around  items-center">
        <h1 class=" font-bold  text-2xl">card title</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
        <a href="#" class="border rounded-md w-24 p-1 bg-blue-600 text-white text-center">know more</a>
    </div>

    <div class="card h-52 w-60 border rounded-md p-5  flex flex-col justify-around  items-end">
        <h1 class=" font-bold  text-2xl">card title</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
        <a href="#" class="border rounded-md w-24 p-1 bg-blue-600 text-white text-center">know more</a>
    </div>
</div>
</body>
</html>
```


#### (2) Create slider 
#### ans.
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css"
      integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body>
    <div class="slider mx-auto mt-20 bg-[#2f4357] h-96 w-[80rem] p-3">

      <div class="btn flex items-center justify-around pt-[10rem]">
        <i class="fa-solid fa-angle-left text-[48px] text-[#929da7]"></i>
        <a href="#"  class=" text-lg bg-[#3dc3bd] shadow-lg w-[10rem] text-center p-3 text-white font-semibold">slide 1</a>
        <i class="fa-solid fa-angle-right text-[48px] text-[#929da7]"></i>
      </div>

        <div class="icons flex justify-center mt-20 gap-4 text-4xl">
          <i class="fa-solid fa-window-minimize text-slate-500"></i>
          <i class="fa-solid fa-window-minimize text-slate-500"></i>
          <i class="fa-solid fa-window-minimize text-slate-500"></i>
      </div>
      
    </div>
  </body>
</html>
```


#### (3) Create table using Tailwind also apply effective color
#### ans.
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body class="border-4 border-slate-600 w-[800px] mx-auto my-7">
    <table class="table-auto mx-auto mt-20 ">
      <caption>
        <h1 class="font-bold  text-2xl text-left p-2">basic table</h1>
        <h2 class="text-left p-2">basic table with card</h2>
      </caption>
      <thead>
        <tr class="border-b-2 border-black-500">
          <th class="p-4">NAME</th>
          <th class="p-4">ID NO.</th>
          <th class="p-4">CREATED NO.</th>
          <th class="p-4">STATUS</th>
        </tr>
      </thead>
      <tbody>
        <tr class="border-b-2 border-black-500">
          <td class="p-8">samso park</td>
          <td class="p-8">34424433</td>
          <td class="p-8">12 may 2017</td>
          <td class="p-8">
            <span class="p-1.5 text-white bg-red-600">pending</span>
          </td>
        </tr>
        <tr class="border-b-2 border-black-500">
          <td class="p-8">marlo sanki</td>
          <td class="p-8">53254532</td>
          <td class="p-8">15 may 2015</td>
          <td class="p-8">
            <span class="p-1.5 bg-yellow-400">IN progress</span>
          </td>
        </tr>
        <tr class="border-b-2 border-black-500">
          <td class="p-8">john ryte</td>
          <td class="p-8">53275533</td>
          <td class="p-8">14 may 2017</td>
          <td class="p-8">
            <span class="p-1.5 text-white bg-cyan-500">FIXED</span>
          </td>
        </tr>
        <tr class="border-b-2 border-black-500">
          <td class="p-8">peter</td>
          <td class="p-8">53275534</td>
          <td class="p-8">16 may 2017</td>
          <td class="p-8">
            <span class="p-1.5 text-white bg-green-500">COMPLETED</span>
          </td>
        </tr>
        <tr>
          <td class="p-8">dave</td>
          <td class="p-8">53275535</td>
          <td class="p-8">20 may 2017</td>
          <td class="p-8">
            <span class="p-1.5 bg-yellow-400">IN progress</span>
          </td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
```