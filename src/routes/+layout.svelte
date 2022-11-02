<ul>
    <li><h3><a href="/">Home</a></h3></li>
    <li><h3><a href="/about">About</a></h3></li>
</ul>
<slot></slot>

<style>
    ul{
        list-style: none;
        display: flex;
    }
    li{
        padding: 0 8px;
    }
    a{
        text-decoration: none;
        color: rgb(0, 0, 0);
        text-decoration: overline;
    }
</style>