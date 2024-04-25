FROM python:3.9

# Copia el archivo .pkl a la imagen
COPY final_model.pkl /app/

# Comando por defecto para ejecutar al iniciar el contenedor
CMD ["python", "-c", "print('final_model.pkl insertado en la imagen.')"]
