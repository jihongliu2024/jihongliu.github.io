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
</head>
<body>

<form id="myForm">
    <label for="name">Name:</label><br>
    <input type="text" id="name" name="name"><br>
    <label for="institute">Institute:</label><br>
    <input type="text" id="institute" name="institute"><br>
    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email"><br><br>
    <button type="submit">Submit</button>
</form>

<script>
document.getElementById("myForm").addEventListener("submit", function(event) {
    event.preventDefault(); // 阻止表单默认提交行为

    // 获取输入的值
    var name = document.getElementById("name").value;
    var institute = document.getElementById("institute").value;
    var email = document.getElementById("email").value;

    // 这里可以在控制台输出获取到的值，也可以进行其他处理，比如发送到服务器
    console.log("Name: " + name);
    console.log("Institute: " + institute);
    console.log("Email: " + email);

    // 清空表单
    // document.getElementById("myForm").reset();
});
</script>
</body>
</html>

Your details will not be distributed but only used to inform you with toolbox updates.
