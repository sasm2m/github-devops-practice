```markdown
# 🚀 GitHub DevOps Practice

Repositorio de práctica para dominar GitHub, CI/CD, y DevOps.

## 📁 Estructura del Proyecto

```

github-devops-practice/
├── .github/
│   ├── workflows/      ← Automatización (GitHub Actions)
│   └── ISSUE_TEMPLATE/ ← Templates para issues
├── src/                ← Código fuente
├── tests/              ← Tests automáticos
├── docs/               ← Documentación
├── .gitignore          ← Archivos que NO suben a GitHub
├── .env.example        ← Ejemplo de variables de entorno
├── package.json        ← Dependencias del proyecto
└── README.md           ← Este archivo

```

## 🎯 Objetivos de Aprendizaje

- ✅ Estructura profesional de repositorios
- ✅ Manejo de ramas (branching)
- ✅ GitHub Actions para CI/CD
- ✅ Manejo seguro de credenciales
- ✅ Tags y Releases

## 🚀 Cómo Empezar

1. Clona este repositorio
2. Sigue los pasos de la documentación
3. Crea tu primer workflow

## 📝 Convención de Commits

Usa estos prefijos en tus commits:

- `feat:` - Nueva característica
- `fix:` - Corrección de bug
- `docs:` - Cambios en documentación
- `style:` - Cambios sin lógica
- `refactor:` - Reorganización de código
- `test:` - Agregar tests
- `chore:` - Tareas administrativas
- `ci:` - Cambios en CI/CD

**Ejemplo:** `git commit -m "feat: agregar validación de emails"`

## 📜 Licencia

MIT - Libre para usar y modificar
```

### 2.5 Archivo `COMMIT_TYPES.md`

Crea `docs/COMMIT_TYPES.md`:

```markdown
# 📝 Tipos de Commits (Conventional Commits)

Usa estos prefijos al hacer commits para mantener un historial claro:

| Tipo | Uso | Ejemplo |
|------|-----|---------|
| `feat:` | Nueva característica | `feat: agregar autenticación` |
| `fix:` | Bug fix | `fix: resolver error de login` |
| `docs:` | Documentación | `docs: actualizar README` |
| `style:` | Formato/espacios | `style: formatear código` |
| `refactor:` | Reorganización | `refactor: simplificar función` |
| `test:` | Tests | `test: agregar tests de auth` |
| `chore:` | Tareas admin | `chore: actualizar npm` |
| `ci:` | CI/CD | `ci: agregar GitHub Actions` |

## ✅ Beneficios

- Historial de cambios **legible**
- Cambios **trazables**
- Facilita **búsquedas**
- Profesional ante otros developers

## 🚫 Lo que NO debes hacer

```bash
# ❌ MALO
git commit -m "cambios"
git commit -m "arreglé esto"
git commit -m "falta una coma"

# ✓ BIEN
git commit -m "fix: resolver error en validación"
git commit -m "docs: mejorar instrucciones de setup"
git commit -m "style: agregar point and comma"
```

```
