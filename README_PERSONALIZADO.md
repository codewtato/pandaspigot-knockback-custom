# 🐼 PandaSpigot - Edición con Knockback Personalizado

Fork de PandaSpigot 1.8.8 con modificaciones avanzadas de knockback para PvP.

## ⚡ Modificaciones de Knockback Implementadas

Este build incluye las siguientes configuraciones avanzadas de knockback:

```yaml
knockback:
  knockback-multiplier: 1.0      # Multiplicador general de knockback
  hit-delay: 1                   # Delay entre hits
  wtap-multiplier: 1.0           # Multiplicador para W-Tap
  strafe-multiplier: 1.0         # Multiplicador para strafe
  rod-multiplier: 0.95           # Multiplicador para caña de pescar
  advanced-hit-detection: true   # Detección avanzada de hits
  velocity-multiplier: 1.0       # Multiplicador de velocidad
  optimized-tps: true           # TPS optimizado
  max-player-packets: 100       # Máximo de paquetes por jugador
  friction-horizontal: 2.0       # Fricción horizontal
  friction-vertical: 1.5         # Fricción vertical
  sprint-multiplier: false       # Multiplicador de sprint
  reduction: 1.0                 # Reducción general
```

## 🛠️ Compilación

Este repositorio está configurado con GitHub Actions para compilación automática.

### Descargar JAR pre-compilado:
1. Ve a la pestaña "Actions" 
2. Selecciona el build más reciente exitoso
3. Descarga el artifact "PandaSpigot-JAR"

### Compilación manual (Linux/WSL):
```bash
./panda setup
./panda jar
```

## 📋 Configuración del Servidor

Una vez que tengas el JAR, crea un archivo `pandaspigot.yml` en tu servidor:

```yaml
worlds:
  default:
    knockback:
      knockback-multiplier: 1.0
      hit-delay: 1
      wtap-multiplier: 1.0
      strafe-multiplier: 1.0
      rod-multiplier: 0.95
      advanced-hit-detection: true
      velocity-multiplier: 1.0
      optimized-tps: true
      max-player-packets: 100
      friction-horizontal: 2.0
      friction-vertical: 1.5
      sprint-multiplier: false
      reduction: 1.0
```

## 🎯 Créditos

- **PandaSpigot Original**: [hpfxd/PandaSpigot](https://github.com/hpfxd/PandaSpigot)
- **Modificaciones de Knockback**: Implementadas por usuario personalizado

---
*Build automatizado con GitHub Actions* ⚡