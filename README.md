<!DOCTYPE html>
<html>
<head>
    <title>Registro de Apartamento</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .container {
            width: 100%;
            max-width: 600px;
            margin: 0 auto;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .form-group input,
        .form-group select {
            width: 100%;
            padding: 10px;
            font-size: 16px;
        }
        .form-group button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        .form-group button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Registro de Apartamento</h1>
        <div class="form-group">
            <label for="number">Número do Apartamento</label>
            <input id="number" name="number" type="text" />
        </div>
        <div class="form-group">
            <label for="rooms">Quantidade de Quartos</label>
            <input id="rooms" name="rooms" type="number" />
        </div>
        <div class="form-group">
            <label for="occupancy">Tipo de Ocupação</label>
            <select id="occupancy" name="occupancy">
                <option value="proprietário">Proprietário</option>
                <option value="inquilino">Inquilino</option>
                <option value="vazio">Vazio</option>
            </select>
        </div>
        <div class="form-group">
            <label for="ownerName">Nome do Proprietário</label>
            <input id="ownerName" name="ownerName" type="text" />
        </div>
        <div class="form-group">
            <label for="ownerPhone">Telefone do Proprietário</label>
            <input id="ownerPhone" name="ownerPhone" type="text" />
        </div>
        <div class="form-group">
            <button type="submit">Registrar</button>
        </div>
    </div>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <title>Lançamento de Despesas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .container {
            width: 100%;
            max-width: 600px;
            margin: 0 auto;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .form-group input,
        .form-group select,
        .form-group textarea {
            width: 100%;
            padding: 10px;
            font-size: 16px;
        }
        .form-group button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        .form-group button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Lançamento de Despesas</h1>
        <div class="form-group">
            <label for="month">Mês</label>
            <input id="month" name="month" type="month" />
        </div>
        <div class="form-group">
            <label for="condoExpense">Despesa do Condomínio</label>
            <input id="condoExpense" name="condoExpense" type="number" step="0.01" />
        </div>
        <div class="form-group">
            <label for="apartmentNumbers">Número(s) do(s) Apartamento(s)</label>
            <input id="apartmentNumbers" name="apartmentNumbers" type="text" placeholder="Exemplo: 101, 102" />
        </div>
        <div class="form-group">
            <label for="apartmentExpense">Despesa Específica do Apartamento</label>
            <input id="apartmentExpense" name="apartmentExpense" type="number" step="0.01" />
        </div>
        <div class="form-group">
            <label for="expenseDescription">Descrição da Despesa</label>
            <textarea id="expenseDescription" name="expenseDescription" rows="4"></textarea>
        </div>
        <div class="form-group">
            <button type="submit">Registrar</button>
        </div>
    </div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>Registro de Condomínio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .container {
            width: 100%;
            max-width: 600px;
            margin: 0 auto;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .form-group input,
        .form-group select {
            width: 100%;
            padding: 10px;
            font-size: 16px;
        }
        .form-group button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        .form-group button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Registro de Condomínio</h1>
        <div class="form-group">
            <label for="reference">Referência</label>
            <input id="reference" name="reference" type="month" />
        </div>
        <div class="form-group">
            <label for="expenseType">Tipo de Despesa</label>
            <select id="expenseType" name="expenseType">
                <option value="fixo">Fundo de Reserva</option>
                <option value="variavel">Água</option>
            </select>
        </div>
        <div class="form-group">
            <label for="expenseValue">Valor da Despesa</label>
            <input id="expenseValue" name="expenseValue" type="number" step="0.01" />
        </div>
        <div class="form-group">
            <label for="totalRooms">Total de Quartos no Prédio</label>
            <input id="totalRooms" name="totalRooms" type="number" />
        </div>
        <div class="form-group">
            <label for="apartmentRooms">Número de Quartos do Apartamento</label>
            <input id="apartmentRooms" name="apartmentRooms" type="number" />
        </div>
        <div class="form-group">
            <label for="paymentDate">Data de Pagamento</label>
            <input id="paymentDate" name="paymentDate" type="date" />
        </div>
        <div class="form-group">
            <label for="paymentAmount">Valor Pago</label>
            <input id="paymentAmount" name="paymentAmount" type="number" step="0.01" />
        </div>
        <div class="form-group">
            <button type="submit">Registrar</button>
        </div>
    </div>
</body>
</html>
