# Welcome to Classboard!
Here at Classboard, we try to provide the best user experience with great UI and easy-to-navigate sections. Take a look around at the cool features we have below!

## Features
🖌 <b>Great UI </b>- With our amazing user interface, you get get where you need to go, fast <br>
🗃 <b>Easy Sections </b> - Our smartly divided sections help you stay organized <br>
📚 <b>Archives </b> - Don't like a change we made? Just travel back to a previous version with the Archives page <br>
🍲 <b>Lunch Menu</b> - We constantly update the lunch menu to let you know what you're consuming next <br>
🌐 <b>Proxies</b> - With our amazing proxy 55GMS by RedNotSus, you can browse the web, play games, watch movies, and so much more without being tracked <br>
⬇ <b>Downloadables</b> - We have lots of downloadables, meaning you can play games, even on the go! <br>
🔐 <b>Secure</b> - Your security matters to us, which is why we try to be as secure as we can <br>
💾 <b>On-Device Data</b> - We don't store your data in servers, it is stored on your device and your device only, meaning no one can see it <br>
🆕 <b>Always Updated</b> - We are constantly updating Classboard, meaning you can expect updates within 2-8 days <br>
💬 <b>Chatrooms</b> - With our chatrooms powered by Microsoft Teams, you can talk to friends and family in real time <br>
💁 <b>Amazing Support</b> - We have options for live chat or to fill out a form! We'll get back to you in 3-5 business days <br>

### Members
[![Contributors](https://contrib.rocks/image?repo=superhardalgebraproblems/superhardalgebraproblems.github.io)](https://github.com/superhardalgebraproblems/superhardalgebraproblems.github.io/graphs/contributors)


### Members Contributions to github and Classboard
# Welcome to My Amazing Coding Game Website!

Visitor Count: **<span id="visitorCount">0</span>**

```html
<script>
    // Function to get the value of a cookie by name
    function getCookie(name) {
        const value = `; ${document.cookie}`;
        const parts = value.split(`; ${name}=`);
        if (parts.length === 2) return parts.pop().split(';').shift();
    }

    // Function to set a cookie
    function setCookie(name, value, days) {
        const date = new Date();
        date.setTime(date.getTime() + (days * 24 * 60 * 60 * 1000));
        const expires = `expires=${date.toUTCString()}`;
        document.cookie = `${name}=${value}; ${expires}; path=/`;
    }

    // Function to update the visitor count
    function updateVisitorCount() {
        let count = getCookie('visitorCount');

        if (!count) {
            // If there's no cookie, set the visitor count to 1 and create the cookie
            count = 1;
            setCookie('visitorCount', count, 1); // Expires in 1 day
        } else {
            // If the cookie exists, increment the count
            count = parseInt(count) + 1;
            setCookie('visitorCount', count, 1);
        }

        // Update the displayed visitor count
        document.getElementById('visitorCount').textContent = count;
    }

    // Call the update function when the page loads
    window.onload = updateVisitorCount;
</script>





