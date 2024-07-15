# input-type-radio


.search-institution-input-radio[type="radio"] {
  transform: scale(1.5);
  position: relative;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  outline: none !important;
  border: none;
  background-color: #D9D9D9;
  padding: 10px;
  border-radius: 20px;
}

.search-institution-input-radio[type="radio"]::before {
  content: "";
  display: block;
  width: 8px;
  height: 8px;
  border-radius: 50%;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-53%, -54%);
  box-sizing: border-box;
  visibility: visible;
}

.search-institution-input-radio[type="radio"]:checked{
  background-color: #fff;
}

.search-institution-input-radio[type="radio"]:checked::before {
  border: 6px solid #2F36BF;
  background-color: #2F36BF;
  visibility: visible;
}
