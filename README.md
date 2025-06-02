
        body {
            font-family: Arial, sans-serif;
            background-color: #eef;
            text-align: center;
            padding: 50px;
        }
        form {
            background-color: white;
            padding: 30px;
            display: inline-block;
            border-radius: 10px;
        }
        input {
            padding: 10px;
            margin: 10px;
            width: 300px;
        }
        button {
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <h1>Pengumuman Kelulusan</h1>
    <h2>SMP Negeri 3 Pangkalan Lesung</h2>
    <form action="hasilkelulusan.html" method="get">
        <input type="text" name="nama" placeholder="Nama Lengkap" required><br>
        <input type="text" name="nisn" placeholder="NISN" required><br>
        <button type="submit">Cek Kelulusan</button>
    </form>
</body>
</html>
