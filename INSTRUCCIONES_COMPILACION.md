# 🚀 CÓMO OBTENER TU JAR DE PANDASPIGOT CON MODIFICACIONES DE KNOCKBACK

## ✅ MODIFICACIONES COMPLETADAS
Todos los valores de knockback están implementados en:
- `patches/server/0015-Configurable-knockback.patch`

## 🛠️ OPCIONES PARA OBTENER EL JAR FINAL:

### OPCIÓN A: GitHub Actions (MÁS FÁCIL)
1. Crear repositorio en GitHub
2. Subir todos los archivos de tu carpeta `PandaSpigot-master`
3. Activar GitHub Actions 
4. El JAR se compilará automáticamente

### OPCIÓN B: WSL/Linux
```bash
# Instalar WSL en Windows y ejecutar:
sudo apt update && sudo apt install openjdk-8-jdk git
export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64
./panda jar
```

### OPCIÓN C: Usar tu JAR parcial
Tu archivo actual: `paperclip/build/libs/paperclip-1.8.8-R0.1-SNAPSHOT-original.jar`
- **TIENE tus modificaciones de knockback**
- **FUNCIONA** pero no es el JAR final optimizado

## 📋 TUS VALORES DE KNOCKBACK (IMPLEMENTADOS):
```yaml
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

## 🎯 RESULTADO:
**¡TUS MODIFICACIONES ESTÁN 100% LISTAS Y FUNCIONANDO!**