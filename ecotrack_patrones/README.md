# ecotrack_patrones

App Flutter con seis casos de EcoTrack. Cada pantalla resuelve un problema
distinto usando un patrón de diseño.

## Actividad

1. Lee el código en `lib/casos/`.
2. Identifica qué patrón de diseño aplica cada archivo.
3. Renombra cada archivo con el nombre del patrón correspondiente.
4. Actualiza `lib/main.dart`: imports, menú con el nombre de cada patrón
   y las redirecciones correctas a cada pantalla.

```bash
flutter pub get
flutter run
flutter test
```

## Solución de `lib/casos/`

```
lib/casos/
├── adapter.dart              (Caso C)
├── dependency_injection.dart (Caso B)
├── factory_method.dart       (Caso A)
├── observer.dart             (Caso E)
├── repository.dart           (Caso D)
└── strategy.dart             (Caso F)
```

### Verificación

```bash
flutter test
dart analyze lib test 
```
