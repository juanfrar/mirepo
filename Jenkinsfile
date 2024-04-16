pipeline {
    agent any

    stages {
        stage('Informar días de la semana') {
            steps {
                script {
                    // Definir los días de la semana
                    def diasSemana = ["Lunes", "Martes", "Miércoles", "Jueves", "Viernes", "Sábado", "Domingo"]
                    
                    // Imprimir todos los días de la semana
                    echo "Los días de la semana son:"
                    for (dia in diasSemana) {
                        echo "- ${dia}"
                    }
                    
                    // Obtener el día de la semana actual
                    def diaActual = new Date().format("EEEE")
                    
                    // Imprimir el día actual
                    echo "Hoy es ${diaActual}."
                }
            }
        }
    }
}
