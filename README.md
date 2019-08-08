# Cr3dOv3r [![Python 3.5](https://img.shields.io/badge/Python-3.5-yellow.svg)](http://www.python.org/download/) [![Python 2.7](https://img.shields.io/badge/Python-2.7-yellow.svg)](http://www.python.org/download/) ![Build Status](https://img.shields.io/badge/Version-0.4.4-red.svg)

**Tu mejor amigo en ataques de reutilización de credenciales.**

Le das un correo electrónico a Cr3dOv3r y luego realiza dos tareas simples y útiles:
- Busca filtraciones públicas para el correo electrónico y devuelve el resultado con los detalles más útiles sobre la filtración (Usando API haveibeenpwned) e intenta obtener las contraseñas de texto sin formato de las filtraciones que encuentra (Usando [@GhostProjectME] (https: // twitter. com / GhostProjectME)).
- Ahora le das una contraseña o una contraseña filtrada, entonces prueba estas credenciales contra algunos sitios web conocidos (por ejemplo: Facebook, Twitter, Google ...), te dice si el inicio de sesión fue exitoso y si hay captcha que bloqueó nuestro camino.

### Algunos de los escenarios en los que se puede usar Cr3dOv3r
- Verificar si el correo electrónico objetivo tiene alguna fuga y luego use la contraseña filtrada para verificarlo en los sitios web.
- Comprobar si las credenciales que posee se reutilizan en otros sitios web / servicios.
- Comprobar si la contraseña anterior que obtuvo del objetivo todavía se utiliza en cualquier sitio web.

# Screenshots
![screenshot](https://github.com/D4Vinci/Cr3dOv3r/blob/master/Data/Email1.png)
![screenshot](https://github.com/D4Vinci/Cr3dOv3r/blob/master/Data/Email2.png)
![screenshot](https://github.com/D4Vinci/Cr3dOv3r/blob/master/Data/Email3.png)

# Uso
```
uso: Cr3d0v3r.py [-h] [-p] [-np] [-q] correo_electrónico

argumentos posicionales:
  correo_electrónico - Correo electrónico / nombre de usuario para verificar

argumentos opcionales:
  -h, - ayuda a mostrar este mensaje de ayuda y salir
  -p No compruebe fugas o contraseñas de texto sin formato.
  -np No compruebe las contraseñas de texto sin formato.
  -q Modo silencioso (sin banner).

```

## Instalación y requisitos
### Para que la herramienta funcione de la mejor manera, debe tener:
- Python 3.xo 2.x (preferido 3).
- Sistema Linux o Windows.

### Instalación
**+ Para Windows: (después de descargar el ZIP y descomprimirlo)**
```
cd Cr3dOv3r-master
python -m pip install -r win_requirements.txt
python Cr3d0v3r.py -h
```
**+ Para Linux:**
```
git clone https://github.com/D4Vinci/Cr3dOv3r.git
cd Cr3dOv3r
python3 -m pip install -r require.txt
python3 Cr3d0v3r.py -h
```

**Si desea agregar un sitio web a la herramienta, siga las instrucciones en [wiki] (https://github.com/D4Vinci/Cr3dOv3r/wiki)**

## Contacto
- [Twitter] (https://twitter.com/D4Vinci1)

## Descargo de responsabilidad
Cr3dOv3r se creó para mostrar cómo los ataques de reutilización de credenciales pueden volverse peligrosos y no es responsable del mal uso o de propósitos ilegales. ¡Úselo solo para Pen-test o para fines educativos!
