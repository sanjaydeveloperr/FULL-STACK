<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>switch</title>
</head>

<body>



    <script>
        function arithmetic(a, b, op) {
            switch (op) {
                case 'plus':
                    return a + b;
                    break;

                case 'minus':
                    return a - b;
                    break;

                case 'power':
                    return a ** b;
                    break;

                case 'multiply':
                    return a * b;
                    break;

                case 'modulus':
                    return a % b;
                    break;

                case 'divide':
                    return a / b;
                    break;


                default:
                    return 'nothing';
                    break;

            }
        }


        console.log(arithmetic(4, 8, "divide"));
    </script>

</body>

</html>
