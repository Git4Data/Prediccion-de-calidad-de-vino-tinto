Este proyecto aplica técnicas de Machine Learning para predecir la calidad del vino tinto a partir del dataset Wine Quality - Red Wine (UCI Machine Learning Repository).
1) Datos: Limpieza, estadistica descriptiva, simetria, kurtosis. Visualizacion de las variables usando histogramas, QQ-Plots y KDE.
2) Pruebas de normalidad para las variables: Shapiro, D´Agostino, Anderson. ECDF y KDE para concluir que los datos no son normales
3) Transformacion: Yeo-Johnson y CoxBox, sigo sin obtener normalidad, opto por crear una nueva variable
4) Creacion de una nueva variable:quality_bin (0,1 y 2). Kruskal wallis
5) Correlaciones: Pearson y Spearman
6) PCA para reducir componentes, distribucion de quality por cluster
7) Aplicar RF y GB, analizar importancia de las variables en la clasificacion de quality_bin. mean SHAP value
9) Luego uso quality para que ahora sea un problema de regresion: RF, Logistic y linear regression
10) Optimización con GridSearchCV
11) Conclusiones
