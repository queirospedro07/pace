# Pace

Aplicação móvel de **gestão de tarefas** desenvolvida em **Ionic + Angular (NgModules)**, no âmbito da unidade curricular de Programação Móvel e Ubíqua (CTeSP TPSI, IPVC ESTG).

## Funcionalidades

- Gestão de **categorias** de projetos (adicionar, editar, eliminar)
- Gestão de **projetos** (nome e categoria); ao eliminar um projeto, as tarefas associadas também são eliminadas
- Visualização de projetos **filtrada por categoria**
- Identificação de **tarefas em atraso**
- Gestão de **tarefas**: título, descrição, data limite e imagem; editar, eliminar, ordenar e mover entre projetos
- **Calendário** com as datas limite; ao selecionar uma tarefa é possível ver e editar os seus dados
- Notificações de proximidade da data limite *(opcional)*

## Requisitos técnicos

- Angular Router (`Router`, `ActivatedRoute`) e passagem de parâmetros entre páginas
- Angular **service** dedicado ao CRUD de tarefas
- Ionic Storage para guardar a informação
- Dados iniciais a partir de ficheiros JSON
- Capacitor (ex.: bloquear a orientação landscape)
- CSS Custom Properties, formatações globais e cores globais
- Componentes reutilizáveis, ícones da framework e código comentado

**Opcionais (valorizam):** dispositivo físico, base de dados/serviço externo, strings isoladas em services/JSON, APIs externas, ícone e splash screen próprios, fontes importadas, Reactive Forms.

## Identidade visual

### Paleta de cores

| Cor | Hex | Uso |
|---|---|---|
| Fundo claro | `#F0FDFF` | Fundo das páginas |
| Escuro | `#1B1F23` | Texto e cabeçalhos |
| Azul claro | `#38BDF8` | Destaques e botões |
| Azul | `#0EA5E9` | Progresso e ações |

Cor de alerta usada nos mockups para tarefas em atraso: `#9F1239` (fundo `#FFE4E6`).
