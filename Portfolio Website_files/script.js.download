console.log('Script is running...')

document.querySelector('.close').style.display = 'none'; // HIDE THE CLOSE BUTTON WHILE OPENING THE WEBSITE

document.querySelector('.hamburger').addEventListener("click", () => {
    document.querySelector('.sidebar').classList.toggle('sidebargo'); // DONT PUT DOT IN THE TOGGLE BRACKET !!!
    if (document.querySelector('.sidebar').classList.contains('sidebargo')) {
        document.querySelector('.ham').style.display = 'inline';
        document.querySelector('.close').style.display = 'none';
    }
    else {
        document.querySelector('.ham').style.display = 'none';
        setTimeout(() => {
            document.querySelector('.close').style.display = 'inline';
        }, 400);
    }
})
