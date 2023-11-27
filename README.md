# Datos de nivel de satisfacción laboral
satisfaccion <- c("Muy insatisfecho", "Insatisfecho", "Regular", "Satisfecho", "Muy satisfecho", "Satisfecho", "Regular", "Satisfecho", "Muy satisfecho", "Insatisfecho", "Regular", "Satisfecho", "Muy satisfecho", "Muy insatisfecho")

# Crear el gráfico de barras
barplot(table(satisfaccion), main="Nivel de satisfacción laboral", xlab="Nivel de satisfacción", ylab="Frecuencia", col="lightgreen")
