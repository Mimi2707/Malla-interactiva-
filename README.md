<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Malla Curricular Interactiva</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Malla Curricular de Medicina</h1>

        <div class="cycle" id="cbc-cycle">
            <h2>Ciclo Básico Común (CBC)</h2>
            <div class="course-list">
                <div class="course" data-course="Int. Pensamiento Científico" data-prerequisites="none">Int. Pensamiento Científico (C)</div>
                <div class="course" data-course="Int. Con. Sociedad y Estado" data-prerequisites="none">Int. Con. Sociedad y Estado (C)</div>
                <div class="course" data-course="Química" data-prerequisites="none">Química (C)</div>
                <div class="course" data-course="Biofísica CBC" data-prerequisites="none">Biofísica (C)</div>
                <div class="course" data-course="Biología Celular" data-prerequisites="none">Biología Celular (C)</div>
                <div class="course" data-course="Matemática" data-prerequisites="none">Matemática (C)</div>
            </div>
        </div>

        <div class="cycle" id="biomedical-clinical-optional">
            <h2>Para Cursar en Ciclo Biomédico o Clínico</h2>
            <div class="course-list">
                <div class="course" data-course="Salud Mental" data-prerequisites="none">Salud Mental (C)</div>
                <div class="course" data-course="Salud Pública" data-prerequisites="none">Salud Pública (C)</div>
                <div class="course" data-course="Bioética" data-prerequisites="none">Bioética (C)</div>
                <div class="course" data-course="Inglés Técnico" data-prerequisites="none">Inglés Técnico</div>
            </div>
        </div>

        <div class="cycle" id="biomedical-cycle">
            <h2>Ciclo Biomédico</h2>
            <div class="year">
                <h3>Primer Año</h3>
                <div class="course-list">
                    <div class="course" data-course="Anatomía" data-prerequisites="Int. Pensamiento Científico, Int. Con. Sociedad y Estado, Química, Biofísica CBC, Biología Celular, Matemática">Anatomía (A)</div>
                    <div class="course" data-course="Histología" data-prerequisites="Int. Pensamiento Científico, Int. Con. Sociedad y Estado, Química, Biofísica CBC, Biología Celular, Matemática">Histología (C)</div>
                    <div class="course" data-course="Embriología" data-prerequisites="Int. Pensamiento Científico, Int. Con. Sociedad y Estado, Química, Biofísica CBC, Biología Celular, Matemática">Embriología (C)</div>
                    <div class="course" data-course="Genética" data-prerequisites="Int. Pensamiento Científico, Int. Con. Sociedad y Estado, Química, Biofísica CBC, Biología Celular, Matemática">Genética (C)</div>
                </div>
            </div>
            <div class="year">
                <h3>Segundo Año</h3>
                <div class="course-list">
                    <div class="course" data-course="Fisiología y Biofísica" data-prerequisites="Anatomía">Fisiología y Biofísica (A)</div>
                    <div class="course" data-course="Bioquímica" data-prerequisites="Anatomía, Histología, Embriología, Genética">Bioquímica (C)</div>
                    <div class="course" data-course="Inmunología" data-prerequisites="Anatomía, Histología, Embriología, Genética">Inmunología (C)</div>
                    <div class="course" data-course="Microbiología" data-prerequisites="Bioquímica, Inmunología">Microbiología (C)</div>
                </div>
            </div>
        </div>

        <div class="cycle" id="clinical-cycle">
            <h2>Ciclo Clínico</h2>
            <div class="course-list">
                <div class="course" data-course="Medicina A" data-prerequisites="Microbiología">Medicina A (C)</div>
                <div class="course" data-course="Patología" data-prerequisites="Microbiología">Patología (C)</div>
                <div class="course" data-course="Farmacología I" data-prerequisites="Microbiología">Farmacología I (C)</div>
                <div class="course" data-course="Medicina Legal y Deontología Médica" data-prerequisites="Microbiología">Medicina Legal y Deontología Médica (C)</div>
                <div class="course" data-course="Toxicología" data-prerequisites="Farmacología I">Toxicología (C)</div>
                <div class="course" data-course="Farmacología II" data-prerequisites="Medicina A, Farmacología I">Farmacología II (C)</div>
            </div>

            <h3>Clínicas</h3>
            <div class="course-list">
                <div class="course" data-course="Medicina B" data-prerequisites="Medicina A, Patología">Medicina B</div>
                <div class="course" data-course="Nutrición" data-prerequisites="Medicina A, Patología">Nutrición</div>
                <div class="course" data-course="Dermatología" data-prerequisites="Medicina A, Patología">Dermatología</div>
                <div class="course" data-course="Infectología" data-prerequisites="Medicina A, Patología">Infectología</div>
                <div class="course" data-course="Neumonología" data-prerequisites="Medicina A, Patología">Neumonología</div>
                <div class="course" data-course="Neurología" data-prerequisites="Medicina A, Patología">Neurología</div>
                <div class="course" data-course="Diagnóstico por Imágenes" data-prerequisites="Medicina A, Patología">Diagnóstico por Imágenes</div>
                <div class="course" data-course="Psiquiatría" data-prerequisites="Medicina A, Patología">Psiquiatría</div>
            </div>

            <h3>Quirúrgicas</h3>
            <div class="course-list">
                <div class="course" data-course="Pedriatía" data-prerequisites="Medicina A, Patología">Pedriatía</div>
                <div class="course" data-course="Obstetricia" data-prerequisites="Medicina A, Patología">Obstetricia</div>
                <div class="course" data-course="Ginecología" data-prerequisites="Medicina A, Patología">Ginecología</div>
                <div class="course" data-course="Cirugía general" data-prerequisites="Medicina A, Patología">Cirugía general</div>
                <div class="course" data-course="Urología" data-prerequisites="Medicina A, Patología">Urología</div>
                <div class="course" data-course="Ortopedia-Traumatología" data-prerequisites="Medicina A, Patología">Ortopedia-Traumatología</div>
                <div class="course" data-course="Oftalmología" data-prerequisites="Medicina A, Patología">Oftalmología</div>
                <div class="course" data-course="Otorrinolaringología" data-prerequisites="Medicina A, Patología">Otorrinolaringología</div>
                <div class="course" data-course="Neurocirugía" data-prerequisites="Medicina A, Patología">Neurocirugía</div>
            </div>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
