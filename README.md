<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Awesome AndroidROM</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f4f8;
            margin: 0;
            padding: 0;
            color: #333;
        }

        h1 {
            font-size: 3rem;
            text-align: center;
            margin-top: 2rem;
            color: #2d2d2d;
            position: relative;
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
        }

        .logo {
            display: block;
            margin: 0 auto;
            width: 150px;
            height: 150px;
            animation: rotate 3s linear infinite;
        }

        @keyframes rotate {
            from {
                transform: rotate(0deg);
            }
            to {
                transform: rotate(360deg);
            }
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 3rem auto;
            background-color: white;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            padding: 2rem;
            border-radius: 10px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 1rem;
        }

        th, td {
            padding: 1rem;
            text-align: center;
            border: 1px solid #ddd;
        }

        th {
            background-color: #4CAF50;
            color: white;
        }

        img {
            max-width: 80px;
            height: auto;
            border-radius: 10px;
        }

        .snippet {
            margin-top: 2rem;
            padding: 1rem;
            background-color: #f5f5f5;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-family: monospace;
        }
    </style>
</head>

<body>

    <h1>Awesome AndroidROM</h1>

    <img src="path_to_your_logo_image" alt="Logo" class="logo">

    <div class="container">
        <table>
            <thead>
                <tr>
                    <th>Icon</th>
                    <th>OEM Name</th>
                    <th>ROM Name</th>
                    <th>Development Status</th>
                    <th>Latest Version</th>
                    <th>Website</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><img src="Icons/ROGUI.png" alt="ROGUI"></td>
                    <td><strong>Asus ROG</strong></td>
                    <td><strong>ROGUI</strong></td>
                    <td>Active</td>
                    <td>14</td>
                    <td><a href="https://www.asus.com/in/content/ui/" target="_blank">Website</a></td>
                </tr>
                <tr>
                    <td><img src="Icons/JoyUI.png" alt="JoyUI"></td>
                    <td><strong>BlackShark</strong></td>
                    <td><strong>JoyUI</strong></td>
                    <td>Discontinued</td>
                    <td>13</td>
                    <td><a href="#">Website</a></td>
                </tr>
                <tr>
                    <td><img src="Icons/DokeOS.png" alt="DokeOS"></td>
                    <td><strong>Blackview</strong></td>
                    <td><strong>DokeOS</strong></td>
                    <td>Active</td>
                    <td>4</td>
                    <td><a href="https://promo.blackview.hk/os3/" target="_blank">Website</a></td>
                </tr>
                <!-- Add more rows as needed -->
            </tbody>
        </table>
    </div>

    <div class="snippet">
        <pre>
| Icon                          | OEM Name     | ROM Name     | Development Status | Latest Version | Website                                     |
| ----------------------------- | ------------ | ------------ | ------------------ | -------------- | ------------------------------------------- |
| <img src="Icons/ROGUI.png">    | Asus ROG     | ROGUI        | Active             | 14             | [Website](https://www.asus.com/in/content/ui/)|
| <img src="Icons/JoyUI.png">    | BlackShark   | JoyUI        | Discontinued       | 13             | [Website]()                                |
| <img src="Icons/DokeOS.png">   | Blackview    | DokeOS       | Active             | 4              | [Website](https://promo.blackview.hk/os3/)  |
        </pre>
    </div>

</body>

</html>
