let count = 0;

const counter = document.getElementById("counter-val");
const increaseBtn = document.getElementById("btn-inc");
const decreaseBtn = document.getElementById("btn-dec");
const themeBtn = document.getElementById("theme-toggle");

// Increase
increaseBtn.addEventListener("click", () => {
    count++;
    counter.textContent = count;
});

// Decrease
decreaseBtn.addEventListener("click", () => {
    count--;
    counter.textContent = count;
});

// Dark Mode Toggle
themeBtn.addEventListener("click", () => {
    document.body.classList.toggle("dark-mode");

    if (document.body.classList.contains("dark-mode")) {
        themeBtn.textContent = "☀️ Light Mode";
    } else {
        themeBtn.textContent = "🌙 Dark Mode";
    }
});
