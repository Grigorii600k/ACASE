<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Опросник</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #E6F7FF; /* Светло-голубой цвет для успокаивающего фона */
            color: #4B0082; /* Темно-фиолетовый цвет для текста */
        }
        h1 {
            color: #2E3A87; /* Темно-синий */
        }
        label {
            font-weight: bold;
        }
        input[type="text"], textarea, select {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            box-sizing: border-box;
            border: 2px solid #4B0082; /* Темно-фиолетовый цвет */
            border-radius: 4px;
            background-color: #F0F8FF; /* Очень светлый голубой для полей ввода */
        }
        button {
            background-color: #2E3A87; /* Темно-синий */
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #4B0082; /* Темно-фиолетовый цвет */
        }
    </style>
    <script>
        function submitForm(event) {
            event.preventDefault();
            const companyName = document.getElementById("companyName").value;
            const questions = document.querySelectorAll(".question");
            const scales = document.querySelectorAll(".scale");
            let valid = true;
            let answers = {};

            questions.forEach((question, index) => {
                if (question.value.trim() === '') {
                    alert(`Заполните поле: Вопрос ${index + 1}`);
                    valid = false;
                }
                answers[`Вопрос ${index + 1}`] = question.value;
            });

            scales.forEach((scale, index) => {
                answers[`Шкала ${index + 1}`] = scale.value;
            });

            if (companyName.trim() === '') {
                alert('Заполните поле: Название Вашей компании');
                valid = false;
            }

            if (valid) {
                let docContent = `Результаты опроса для ${companyName}\n\n`;
                let questionIndex = 1;

                questions.forEach((question, index) => {
                    docContent += `${questionIndex}. ${question.previousElementSibling.innerText}\nОтвет: ${question.value}\n\n`;
                    questionIndex++;
                    if (index < scales.length) {
                        docContent += `${questionIndex}. ${scales[index].previousElementSibling.innerText}\nОтвет: ${scales[index].value}\n\n`;
                        questionIndex++;
                    }
                });

                const blob = new Blob([docContent], { type: 'application/msword' });
                const link = document.createElement('a');
                link.href = URL.createObjectURL(blob);
                link.download = `${companyName}_results.doc`;
                link.click();

                alert('Результаты сохранены!');
            }
        }
    </script>
</head>
<body>
    <h1>Опросник</h1>
    <form onsubmit="submitForm(event)">
        <label for="companyName">Название компании</label>
        <input type="text" id="companyName" name="companyName" required><br><br>

        <div>
            <h2>Ассортимент</h2>
            <label for="q1">1. Насколько вы удовлетворены ассортиментом отелей</label>
            <textarea id="q1" class="question" required></textarea><br><br>
            <label for="s1">2. Оцените удобство каталога отелей по шкале от 1 до 10</label>
            <select id="s1" class="scale" required>
                <option value="">Выберите</option>
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
                <option value="4">4</option>
                <option value="5">5</option>
                <option value="6">6</option>
                <option value="7">7</option>
                <option value="8">8</option>
                <option value="9">9</option>
                <option value="10">10</option>
            </select><br><br>

            <h2>Качество информации</h2>
            <label for="q2">3. Как вы оцениваете качество информации, предоставляемой нами об отелях (описания, фото, доступность)</label>
            <textarea id="q2" class="question" required></textarea><br><br>
            <label for="s2">4. Оцените конкурентоспособность наших цен по шкале от 1 до 10</label>
            <select id="s2" class="scale" required>
                <option value="">Выберите</option>
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
                <option value="4">4</option>
                <option value="5">5</option>
                <option value="6">6</option>
                <option value="7">7</option>
                <option value="8">8</option>
                <option value="9">9</option>
                <option value="10">10</option>
            </select><br><br>

            <h2>Поддержка</h2>
            <label for="q3">5. Сталкивались ли вы с какими-либо затруднениями при бронировании отелей через нашу платформу? Если да, опишите их</label>
            <textarea id="q3" class="question" required></textarea><br><br>
            <label for="s3">6. Оцените качество нашей службы поддержки по шкале от 1 до 10</label>
            <select id="s3" class="scale" required>
                <option value="">Выберите</option>
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
                <option value="4">4</option>
                <option value="5">5</option>
                <option value="6">6</option>
                <option value="7">7</option>
                <option value="8">8</option>
                <option value="9">9</option>
                <option value="10">10</option>
            </select><br><br>

            <h2>Улучшения</h2>
            <label for="q4">7. Что бы вы хотели улучшить в нашем сервисе</label>
            <textarea id="q4" class="question" required></textarea><br><br>
            <label for="s4">8. Насколько вероятно, что вы будете продолжать сотрудничать с нами в будущем по шкале от 1 до 10</label>
            <select id="s4" class="scale" required>
                <option value="">Выберите</option>
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
                <option value="4">4</option>
                <option value="5">5</option>
                <option value="6">6</option>
                <option value="7">7</option>
                <option value="8">8</option>
                <option value="9">9</option>
                <option value="10">10</option>
            </select><br><br>
        </div>

        <button type="submit">Сохранить результаты</button>
    </form>
</body>
</html>
