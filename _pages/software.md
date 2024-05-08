---
layout: archive
title: "Software"
redirect_from: 
  - /software/
  - /software.html
sidebar:
  nav: "main"
---

## SM-VCE
A Method for Measuring 3-D Surface Deformations With InSAR Based on Strain Model and Variance Component Estimation.

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Form Example</title>
<style>
    .hidden {
        display: none;
    }
</style>
</head>
<body>

<button id="showForm">Show Form</button>

<form id="collectInfoForm" class="hidden">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name"><br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email"><br>
    <button type="submit" id="submitForm">Submit</button>
</form>

<div id="message" class="hidden"></div>

<script>
document.getElementById("showForm").addEventListener("click", function() {
    document.getElementById("collectInfoForm").classList.remove("hidden");
});

document.getElementById("collectInfoForm").addEventListener("submit", function(event) {
    event.preventDefault(); // Prevent form submission
    var name = document.getElementById("name").value;
    var email = document.getElementById("email").value;
    var message = document.getElementById("message");
    
    // Do something with the collected information
    // For example, you can send it to a server using AJAX
    
    // Show a message to the user
    message.textContent = "Form submitted successfully!";
    message.classList.remove("hidden");
    
    // Simulate redirecting to a download link
    setTimeout(function() {
        window.location.href = "https://github.com/jihongliu2024/jihongliu2024.github.io.git";
    }, 3000); // Redirect after 3 seconds
});
</script>

</body>
</html>
