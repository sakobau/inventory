<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sales and Inventory System</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Product List</h1>
        <table id="productTable">
            <thead>
                <tr>
                    <th>Product Name</th>
                    <th>Description</th>
                    <th>Price</th>
                    <th>Stock</th>
                    <th>Action</th>
                </tr>
            </thead>
            <tbody id="productList">
                <!-- سيتم ملء المنتجات هنا ديناميكيًا بواسطة JavaScript -->
            </tbody>
        </table>
    </div>

    <!-- نافذة منبثقة لتسجيل مبيعات جديدة -->
    <div id="saleModal" class="modal">
        <div class="modal-content">
            <span class="close">&times;</span>
            <h2>New Sale</h2>
            <form id="saleForm">
                <label for="saleQuantity">Quantity:</label>
                <input type="number" id="saleQuantity" name="quantity" min="1" required>
                <button type="submit">Submit Sale</button>
            </form>
        </div>
    </div>

    <script src="app.js"></script>
</body>
</html>
