<!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<button onclick="CustomerCreditCardDetails('mounisha,'452375845634','1122','173')">complete details</button>
<p id="bank"></p>
<script>
function CustomerCreditCardDetails(name,cardNUMBER,expDate,cvvNUMBER)
{
document.getElementById("bank").innerHTML= " " + name + " " cardNUMBER+ "" + expDate+ " "+ cvvNUMBER;
}

</script>
</body>
</html>
