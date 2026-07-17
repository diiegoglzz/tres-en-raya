# Tres en Raya

Juego de Tres en Raya (Tic-Tac-Toe) hecho en Python con Tkinter.

## Características

- Interfaz gráfica simple con Tkinter.
- Cara o cruz al inicio y en cada reinicio para decidir quién empieza (X u O).
- Detección automática de ganador (filas, columnas y diagonales).
- Detección de empate.
- Botón de reinicio que reinicia el tablero y vuelve a sortear el turno inicial.

## Requisitos

- Python 3.x
- Tkinter (viene incluido por defecto en la mayoría de instalaciones de Python)

## Instalación

Clona el repositorio:

```bash
git clone https://github.com/diiegoglzz/tres-en-raya.git
cd tres-en-raya
```

(Opcional) crea y activa un entorno virtual:

```bash
python3 -m venv venv
source venv/bin/activate
```

## Uso

Ejecuta el juego con:

```bash
python3 main.py
```

Se mostrará un aviso indicando qué jugador empieza (X u O), y después podrás jugar haciendo clic en las casillas. Al terminar la partida, puedes pulsar el botón **Reiniciar** para jugar de nuevo (se volverá a sortear quién empieza).

## Estructura del proyecto

```
tres-en-raya/
├── main.py
├── .gitignore
└── README.md
```

## Autor

Diego ([@diiegoglzz](https://github.com/diiegoglzz))
