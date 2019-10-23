<script>
	let name = 'world';
</script>

<style>
  #app {
    display: flex;
    height: inherit;
  }
  .sidebar {
    flex: 1;
    background-color: #97A7FF;
    box-shadow: 2px 0px 7px rgba(0, 0, 0, 0.25);
    position: relative;
  }
  .content {
    flex: 5;
  }

  .navbar li {
    list-style: none;
    margin-right: 1rem;
    font-weight: 700;
    color: #97A7FF;
    font-size: 1.25rem;
    font-family: Helvetica, sans-serif;
    border-bottom: 3px solid transparent;
    transition: 0.25s;
    cursor: pointer;
  }

  .navbar li:hover {
    color: #696969;
    border-bottom: 3px solid #97A7FF;
  }

  .navbar {
    display: flex;
    position: absolute;
    bottom: 0;
    right: 0;
    margin: 1rem;
  }

  #code {
    position: absolute;
    width: 100%;
    opacity: 0.02;
    height: 100%;
    object-fit: cover;
  }

  .logo {
    font-size: 5rem;
    color:#fff;
    font-weight: bold;
    text-align: center;
    margin: 0;
  }
</style>

<div id="app">
	<aside class="sidebar">
  <img id="code" src="../images/code.jpg" alt="code"/>
	<h1 class="logo"> J </h1>
	</aside>
  <div class="content">
    <nav class="navbar">
      <li>ABOUT</li>
      <li>WORK</li>
      <li>CONTACT</li>
    </nav>
  </div>
</div>
