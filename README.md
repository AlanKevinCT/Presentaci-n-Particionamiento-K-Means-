Este repositorio contiene el código fuente para generar la **Quarto Page** y el **Documento PDF** requeridos para la evaluación de K-Means.

---

## 🚀 Requisitos Previos

Antes de compilar, asegúrate de tener instalado en tu computadora:
1. [Quarto CLI](https://quarto.org/docs/get-started/)
2. Una distribución de LaTeX para generar el PDF. Si no tienes una, instala la versión ligera oficial de Quarto ejecutando este comando en tu terminal:
   ```bash
   quarto install tinytex

## Compilar y Generar documentos
Para generar simultáneamente la página web interactiva (HTML) y el documento técnico formal (PDF), abre una terminal en la raíz de esta carpeta y ejecuta:
   ```bash
   quarto render
   ```

## Limpieza y Re-renderizado
Si realizas cambios en el diseño, las fórmulas o el código de Python y notas que no se reflejan, o si la compilación se traba, debes limpiar la caché acumulada de Quarto antes de volver a compilar. Elimmina la carpeta 'docs' y usa el siguiente comando en tu terminal:
   ```bash
   quarto render
   ```

## Esta es la presentación para exponer
https://canva.link/0owwrafy1efrszc 

## Sitio de GitHub pages:
https://alankevinct.github.io/Presentaci-n-Particionamiento-K-Means-/ 