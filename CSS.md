body {
  margin: 0;
  padding: 30px;
  font-family: Arial, sans-serif;
  background: #f3f6fa;
  color: #203040;
}

.card {
  width: 260px;
  margin: 20px;
  border-radius: 10px;
}

.card h2 {
  margin-top: 0;
}

.card-one {
  box-sizing: content-box;
  padding: 20px;
  border: 5px solid steelblue;
  background: #e4f0ff;
}

.card-two {
  box-sizing: border-box;
  padding: 20px;
  border: 5px solid seagreen;
  background: #e5f7ed;
}

.card-three {
  box-sizing: border-box;
  width: 320px;
  margin: 35px 20px;
  padding: 12px 28px;
  border: 8px dashed darkorange;
  background: #fff1dc;
}

/* Box model illustration */
.box-model {
  width: 420px;
  margin: 40px 20px;
  text-align: center;
}

.margin {
  padding: 24px;
  background: #ffe5b4;
  border: 2px dashed #bd7b13;
}

.border {
  padding: 20px;
  background: #f3c9c9;
  border: 8px solid #b84c4c;
}

.padding {
  padding: 22px;
  background: #cfe1ff;
}

.content {
  padding: 18px;
  background: #c9efd9;
  font-weight: bold;
}

.margin > span,
.border > span,
.padding > span {
  display: block;
  margin-bottom: 8px;
  font-size: 14px;
  font-weight: bold;
}