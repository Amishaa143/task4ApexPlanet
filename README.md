<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Task 4</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="task4.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.3.0/font/bootstrap-icons.css">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-primary">
        <div class="container-fluid">
            <a href="#" class="navbar-brand">Portfolio</a>
            <button type="button" class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="navbarCollapse">
                <i class="bi bi-list"></i>
            </button>
            <div class="collapse navbar-collapse" style="color:white;" id="navbarCollapse">
                <div class="navbar-nav ms-auto">
                    <a href="#home" class="nav-item nav-link active">Home</a>
                    <a href="#projects" class="nav-item nav-link active">Projects</a>
                    <a href="#about-me" class="nav-item nav-link active">About Me</a>
                    <a href="#skills" class="nav-item nav-link active">Skills</a>
                    <a href="#contactMe" class="nav-item nav-link active">Contact Me</a>
                    <a href="#todo" class="nav-item nav-link active">To-Do List</a>
                    <a href="#products-store" class="nav-item nav-link active">Products</a>
                </div>
            </div>
        </div>
    </nav>
    <main>
        <section id="home" class="section">
            <br><br>
            <p style="font-weight: 700; font-size: 2rem;">HI,
            </p>
            <h2 class="typing"style="color:red; background: url(amishaphoto.jpg) no repeat right end; padding-right: 50px; background-size: 30px 30px; display: inline-block;">
            I am Amisha! <span class="typing text">FrontEnd Developer</span></h2>
            <div class="para">
                <p>I am a passionate and detail-oriented Web Developer with a strong foundation in front-end development, problem-solving.<br>I enjoy turning ideas into functional, efficient, and visually appealing outcomes that add real value.
            </p>
            </div>
        </section>
       <br><br>
       <section id="projects" class="section">
           <h2>Projects</h2>
           <br><br>
           <div class="project-container">
<div class="card" style="width:400px; left:10px;">
    <img src="portfolio.jpg" alt="Portfolio Image" width="400px">
    <div class="card-title text-center" style="font-weight: 700;">Portfolio Website</div>
    <div class="card-body text-center">
        <p class="card-text">A portfolio is a collection of work, achievements, and skills that showcases your abilities, experiences, and accomplishments in a particular field.</p>
    </div>
    </div>
<div class="card" style="width:400px; left:10px;">
    <img src="todo.jpg" alt="To-Do list Image">
    <div class="card-title text-center" style="font-weight: 700;">To-Do-List</div>
    <div class="card-body text-center">
        <p class="card-text">To-Do-List helps the user to add tasks that they have done or must be done by user and helps to delete them too on completion.</p>
    </div>
    </div>
<div class="card" style="width:400px; left:10px;">
    <img src="grade.png" alt="Grade traker Image" width="400px" height="200px" >
    <div class="card-title text-center"style="font-weight: 700;">Student Grade Treker</div>
    <div class="card-body text-center">
        <p class="card-text">Student Grade Treker helps to calculate students grades according to individual subject marks and then calculate average,highest and lowest of all students. </p>
    </div>
    </div>
</div>
<br><br><br><br><br><br>
       </section>
     <section id="about-me" class="section" >
         <div class="para-about">
        <div class="profile">
            <div class="card-img">
             <img src="amishaphoto.jpg" alt="Image" class="self-img">
             </div>
             </div>
             <div class="intro">
    <h2>About ME</h2> 
<p>"I am a curious and enthusiastic learner with a strong interest in technology, problem-solving, and creativity.
     I enjoy exploring new ideas, developing practical solutions, and continuously improving my skills. With a positive mindset and adaptability.
     I aim to grow both personally and professionally while contributing meaningfully wherever I work.
     I am a dedicated and detail-oriented individual with a passion for technology and problem-solving. 
     I enjoy working on projects that challenge my skills and allow me to learn continuously. 
     My goal is to grow as a professional while contributing innovative solutions and value to every task I undertake."</p>
</div>
</div>
     </section>
<br><br>
<section id="skills" class="section">
<h2>Skills&nbsp;<i class="bi bi-pen-fill" style="color:white;"></i></h2>
<div class="skill-section">
<p>Skills are  the ability to use one's knowledge effectively and readily in execution or performance.
    My skills are:-
   <ul>
    <h3>Coding Skills</h3>
    <li>HTML-100%</li>
    <li>CSS-90%</li>
    <li>Java-50%</li>
    <li>OOPS-100%</li>
    <li>DBMS</li>
    <li>CN</li>
   </ul>
   <ul>
    <h3>Soft Skills</h3>
    <li>Team Collaboration</li>
    <li>Communication</li>
    <li>Time Management</li>
    <li>Sportsmanship</li>
    <li>Reading</li>
   </ul>
</div>
</section>
<br><br>
<section id="todo" class="section">
     <h2 style="color: blue;">To-Do List</h2>
      <input type="text" id="taskInput" placeholder="Enter task" />
      <button id="addTaskBtn">Add</button>
      <ul id="taskList"></ul>
</section>
<section id="contactMe" class="section">
    <h2>Contact Me &nbsp;<i class="bi bi-person-lines-fill" style="color:white;"></i></h2>
    <br>
    <div class="container">
    <form class="contact-from">
<label for="username" class="form-label">Name:</label>
<input type="text" class="form-control"/>
<label for="email" class="form-label">Email:</label>
<input type="text" class="form-control"/>
<label for="phone" class="form-label">Mobile Number:</label>
<input type="number" class="form-control"/>
<label for="message" class="form-label">Message:</label><br>
<textarea name="textarea" id="message" placeholder="Enter your query" style="width:400px; height: 200px;"></textarea> 
<br><br>
<div class="d-grid">
<button class="btn btn-success active btn-lg">Send Message</button>
</div>
</div>
    </form>
</section> 
<br><br>
<section class="section" id="products-store">
    <h2>Store Market</h2>
    <h3 style="text-align: center;;">Shop by Filters</h3>
    <br>
    <div class="filters">
        <label style="font-weight: 700; line-height: 10px; align-self: center;">Category:</label>
        <select id="categoryFilter">
            <option value="all">All Categories</option>
            <option value="clothes">Clothes</option>
            <option value="trousers">Trousers</option>
            <option value="shoes">Shoes</option>
        </select>
        
        <select id="priceFilter">
            <option value="all">All Prices</option>
            <option value="under1000">Under $1000</option>
            <option value="1000to2000">$1000-$2000</option>
            <option value="above2000">Above $2000</option>
        </select>
      
        <select id="sortRating">
            <option value="none">Sort By Rating</option>
            <option value="high">High to Low</option>
            <option value="low">Low To High</option>
        </select>
    </div>
  <div class="product-grid" id="productGrid"></div>
</section> 
    </main>
    <br><br><br><br>
    <footer>
        <p>&copy;2025 Amisha Saini</p>
    </footer>
    <script src="script4.js">
    </script>
    <script>
         const products = [
      {  name: "Crop-Tops", category: "Clothes", price: 300,rating:4.5 },
      {  name: "Jeans", category: "Clothes", price: 800, rating:4.0 },
      {  name: "T-Shirt", category: "Clothes", price: 600,rating:3.9 },
      {  name: "Cargo", category: "Trousers", price: 1500,rating:4.2 },
      {  name: "Formal-pants", category: "Trousers", price: 1800, rating:4.1 },
      {  name: "Puma", category: "Shoes", price: 3500, rating:4.6 },
      {  name: "Nike", category: "Shoes", price: 4000, rating:4.7 },
    ];

    const productList = document.getElementById("productGrid");
    const categoryFilter = document.getElementById("categoryFilter");
    const priceFilter = document.getElementById("priceFilter");
    const sortRating = document.getElementById("sortRating");

    function displayProducts(items) {
      productGrid.innerHTML = '';
      items.forEach(p => {
       productList.innerHTML+=`
       <div class="product"
       <h3>${p.name}</h3>
       <p class="price">$${p.price}</p>
       <p class="rating">&#x2B50;${p.rating}</p>
       <p><small>${p.category}</small></p>
       </div>
       `;
      });
    }

    function FilterAndSort() {
      let filtered = [...products];

      // Filter
      const category= categoryFilter.value;
      if (category !== 'all') {
        filtered = filtered.filter(p => p.category === category);
      }
      //pricefilter
      const price=priceFilter.value;
      filtered=filtered.filter(p=> 
      {
        if(price=== 'under1000') return p.price<1000;
        if(price=== '1000to2000') return p.price>1000 && p.price<=2000;
        if(price=== 'above2000') return p.price>=2000;
        return true;
      });

      // Sort
      const sort = sortRating.value;
      if (sort === 'low') {
        filtered.sort((a, b) => b.rating - a.rating);
      } else if (sort=== 'high') {
        filtered.sort((a, b) => a.rating - b.rating);
      } 
      displayProducts(filtered);
    }

   categoryFilter.addEventListener('change',FilterAndSort);
   priceFilter.addEventListener('change',FilterAndSort);
   sortRating.addEventListener('change',FilterAndSort);
displayProducts(products);
    </script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/js/bootstrap.bundle.min.js"></script>
</body>
    </html>
