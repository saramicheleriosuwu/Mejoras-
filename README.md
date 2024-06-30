# Mejoras de TP de Testing

<form id="registroPacienteForm">
    <label for="historiaClinica">Historia Clínica:</label>
    <input type="text" id="historiaClinica" maxlength="50" required><br>

    <label for="apellido">Apellido:</label>
    <input type="text" id="apellido" maxlength="20" required><br>

    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" maxlength="20" required><br>

    <label for="numeroDocumento">Número de Documento:</label>
    <input type="number" id="numeroDocumento" maxlength="8" required><br>

    <label for="idDocumento">ID Documento:</label>
    <select id="idDocumento" required>
        <option value="LC">LC (Libreta Cívica)</option>
        <option value="DNI">DNI (Documento Nacional de Identidad)</option>
        <option value="PASAPORTE">PASAPORTE</option>
    </select><br>

    <label for="sexo">Sexo:</label><br>
    <input type="radio" id="sexoM" name="sexo" value="M" required>
    <label for="sexoM">M</label><br>
    <input type="radio" id="sexoF" name="sexo" value="F" required>
    <label for="sexoF">F</label><br>

    <button type="submit">Registrarse</button>
</form>
