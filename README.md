# Modelo de Predicción de Cáncer de Mama

Este repositorio contiene un modelo de inteligencia artificial para la predicción de cáncer de mama basado en características extraídas de imágenes de masas mamarias. El modelo utiliza **regresión logística** con optimización de hiperparámetros para clasificar tumores como benignos o malignos.

## Variables de Entrada

El modelo requiere las siguientes características como entrada:

- radius_mean: Media del radio del tumor
- texture_mean: Media de la textura del tumor
- perimeter_mean: Media del perímetro del tumor
- area_mean: Media del área del tumor
- smoothness_mean: Media de la suavidad del tumor
- compactness_mean: Media de la compacidad del tumor
- concavity_mean: Media de la concavidad del tumor
- concave_points_mean: Media de los puntos cóncavos del tumor
- symmetry_mean: Media de la simetría del tumor
- fractal_dimension_mean: Media de la dimensión fractal del tumor
- radius_se: Error estándar del radio
- texture_se: Error estándar de la textura
- perimeter_se: Error estándar del perímetro
- area_se: Error estándar del área
- smoothness_se: Error estándar de la suavidad
- compactness_se: Error estándar de la compacidad
- concavity_se: Error estándar de la concavidad
- concave_points_se: Error estándar de los puntos cóncavos
- symmetry_se: Error estándar de la simetría
- fractal_dimension_se: Error estándar de la dimensión fractal
- radius_worst: Peor valor del radio
- texture_worst: Peor valor de la textura
- perimeter_worst: Peor valor del perímetro
- area_worst: Peor valor del área
- smoothness_worst: Peor valor de la suavidad
- compactness_worst: Peor valor de la compacidad
- concavity_worst: Peor valor de la concavidad
- concave_points_worst: Peor valor de los puntos cóncavos
- symmetry_worst: Peor valor de la simetría
- fractal_dimension_worst: Peor valor de la dimensión fractal

## Salida del Modelo

El modelo devuelve una de las siguientes clasificaciones:

- Malignant: Indica que el tumor es maligno (canceroso)
- Benign: Indica que el tumor es benigno (no canceroso)

## Tecnologias

- FastAPI para la exposición del modelo como API REST
- GitHub Actions para CI/CD
- Docker para la contenerización del modelo

## Estudiante

Esteban Ramírez M  
LEAD UNIVERSITY
