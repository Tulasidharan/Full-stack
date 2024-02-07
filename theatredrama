<!DOCTYPE html>
<html>
<head>
    <title>Ticket Details</title>
    <style>
        div#maincontent {
            height: 200px;
            width: 500px;
            border: 1px solid #CEE2FA;
            text-align: left;
            color: #08438E;
            font-family: calibri;
            font-size: 20;
            padding: 5px;
        }
        div#heading {
            text-decoration: bold;
            text-align: center;
            margin-top: 80px;
            width: 500px;
            border: 1px solid #CEE2FA;
            text-align: center;
            color: #08438E;
            background-color: #CEE2FA;
            font-family: calibri;
            font-size: 20;
            padding: 5px;
        }
        h4 {
            padding: 0; margin: 0;
        }
    </style>
</head>
<body>
    <center>
        <div id="heading">
            <b>Theatre Drama</b>
        </div>
        <div id="maincontent">
            <h4>Your Ticket Details:</h4>
            <br>
            <script>
                function calculateTicketPrices() {
                    var numTickets = 3; // Replace with the actual number of tickets
                    var pricePerTicket = 9;
                    var totalPrice = numTickets * pricePerTicket;
                    var discountPercentage = 10;
                    var discountedAmount = (totalPrice * discountPercentage) / 100;
                    var finalPrice = totalPrice - discountedAmount;

                    // Display results
                    document.write("<p>Total number of seats booked " + numTickets + "</p>");
                    document.write("<p>Total cost of " + numTickets +" tickets: $" + totalPrice + "</p>");
                    document.write("<p>Festive season discount is: " + discountPercentage + "%</p>");
                    document.write("<p>Total cost after discount is: $" + finalPrice.toFixed(1) + "</p>");
                }
                calculateTicketPrices();
            </script>
        </div>
    </center>
</body>
</html>