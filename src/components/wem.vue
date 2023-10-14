<template>
    <header>
        <h1>Badminton Shoes Shop Admin</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#inventory">Inventory</a></li>
            <li><a href="#sales">Sales</a></li>
            <li><a href="#customers">Customers</a></li>
        </ul>
    </nav>
    <main>
        <section id="inventory">
            <h2>Shoe Inventory Management</h2>
            <table>
                <thead>
                    <tr>
                        <th>Product ID</th>
                        <th>Product Name</th>
                        <th>Price</th>
                        <th>Quantity in Stock</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>101</td>
                        <td>Professional Badminton Shoes</td>
                        <td>$80.00</td>
                        <td>50</td>
                    </tr>
                    <tr>
                        <td>102</td>
                        <td>Beginner Badminton Shoes</td>
                        <td>$50.00</td>
                        <td>30</td>
                    </tr>
                    <!-- Add more rows as needed -->
                </tbody>
            </table>
        </section>
        
        <section id="sales">
            <h2>Sales Management</h2>
            <table>
                <thead>
                    <tr>
                        <th>Order ID</th>
                        <th>Customer Name</th>
                        <th>Product Name</th>
                        <th>Quantity Sold</th>
                        <th>Total Price</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>201</td>
                        <td>John Doe</td>
                        <td>Professional Badminton Shoes</td>
                        <td>2</td>
                        <td>$160.00</td>
                    </tr>
                    <tr>
                        <td>202</td>
                        <td>Jane Smith</td>
                        <td>Beginner Badminton Shoes</td>
                        <td>1</td>
                        <td>$50.00</td>
                    </tr>
                    <!-- Add more rows as needed -->
                </tbody>
            </table>
        </section>
        
        <section id="customers">
            <h2>Customer Management</h2>
            <table>
                <thead>
                    <tr>
                        <th>Customer ID</th>
                        <th>Name</th>
                        <th>Email</th>
                        <th>Phone Number</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>301</td>
                        <td>John Doe</td>
                        <td>johndoe@example.com</td>
                        <td>(555) 123-4567</td>
                    </tr>
                    <tr>
                        <td>302</td>
                        <td>Jane Smith</td>
                        <td>janesmith@example.com</td>
                        <td>(555) 987-6543</td>
                    </tr>
                    <!-- Add more rows as needed -->
                </tbody>
            </table>
        </section>
    </main>
</template>
