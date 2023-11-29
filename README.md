# Iris-Helper
Customizable Pixelworks X7 parameter configuration for any App.

# How-to-use
The module supports up to 4 param groups for per App.<br>
Each App should start with<br>
app: "package_name"<br>
Fill the quotes with your package name.<br>
And add your parameters below.<br>

params_a: param_1 param_2 etc.<br>
params_b: param_1 param_2 etc.<br>
...<br>
params_d: params_1 etc.<br>

Example:<br>

app: "com.tencent.tmgp.sgame"<br>
params_a: 267 2 1 3<br>
params_b: 258 2 40 -1 2<br>

Pixelworks X7 supports 4 kinds of parameters, called "type-id".<br>
Input "/odm/bin/irisConfig -help" in Termux for help.<br>
