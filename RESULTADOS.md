# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 4 correctas de 6 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.41 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.33 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.36 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 5: Incorrecto
```diff
--- 
+++ 
@@ -1,7 +1,7 @@
-id | nombre | cuatrimestre | curso | id_grado
-72.00 | Bases moleculares del desarrollo vegetal | 1.00 | 3.00 | 7.00
-73.00 | Fisiología animal | 1.00 | 3.00 | 7.00
-74.00 | Metabolismo y biosíntesis de biomoléculas | 1.00 | 3.00 | 7.00
-75.00 | Operaciones de separación | 1.00 | 3.00 | 7.00
-76.00 | Patología molecular de plantas | 1.00 | 3.00 | 7.00
-77.00 | Técnicas instrumentales básicas | 1.00 | 3.00 | 7.00
+id | nombre | cuatrimestre | id_grado
+72.00 | Bases moleculares del desarrollo vegetal | 1.00 | 7.00
+73.00 | Fisiología animal | 1.00 | 7.00
+74.00 | Metabolismo y biosíntesis de biomoléculas | 1.00 | 7.00
+75.00 | Operaciones de separación | 1.00 | 7.00
+76.00 | Patología molecular de plantas | 1.00 | 7.00
+77.00 | Técnicas instrumentales básicas | 1.00 | 7.00
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 6: Error
- **Descripción**: 'NoneType' object is not iterable

