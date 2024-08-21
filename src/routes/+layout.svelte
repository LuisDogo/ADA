<body style="background-color:rgb(65, 65, 65);"></body>

<ul>
    <li><a href="/browser">browser</a></li>
    <li><a href="/profile">profile</a></li>
    <li><a href="/chats">chats</a></li>
</ul>

<style>
ul {
    list-style-type: none;
    background-color: #333;
    position: fixed;
    bottom: 0;
    width: 100%;
  }
  
li {
    float: left;
  }
  
li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
  }
  
  /* Change the link color to #111 (black) on hover */
li a:hover {
    background-color: #111;
  }

li a:active {
    background-color: #04AA6D;
  }
</style>

<slot></slot>