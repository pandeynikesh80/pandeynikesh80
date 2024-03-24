body {
  margin: 0;
  padding: 0;
  font-family: "HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif; 
  
}

#menuBar {
  width:100%;
  height:40px;
  background-color: #E0E0E0;
  border: 1px solid gray;
}

#logo {
  padding: 10px 0px 0px 20px;
  font-weight: bold;
  font-size: 120%;
  float: left;
}

#buttonDiv {
  float: right;
  padding: 5px 10px 0 0;
}

#runButton {
  font-size: 120%;
}

#toggles {
  width: 193px;
  margin: 0 auto;
  list-style: none;
  border: 1px solid gray;
  border-radius: 3px;
  height: 27px;
  padding: 0;
  margin-top: 5px;
}

#toggles li {
  float: left;
  border-right: 1px solid gray;
  padding: 5px 6px;
}

.clear {
  clear:both;
}

.codeContainer {

  height: 100%;
  width:50%;
  float:left;
  position: relative;
}

.codeContainer textarea {
  width: 100%;
  height:100%;
  border: none;
  border-right: 2px solid gray;
  font-family: Courier;
  font-size: 115%;
  padding: 30px 8px 0 8px;
  /*border-box includes padding and border in width*/
  box-sizing: border-box;
}

.codeLabel {
  position: absolute;
  top: 10px;
  right: 10px;
  font-weight: bold;
}

#CSSContainer, #JSContainer {
  display: none;
}


iframe {
  height: 100%;
  position: relative;
  left: 20px;
  border:none;
}

.selected {
  background-color:gray;
}

**
