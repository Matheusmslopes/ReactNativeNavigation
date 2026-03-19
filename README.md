# 📱 React Native Navigation Study
Repositório criado somente para mexer com navegação e configurações de build para desenvolvimento

## 🛠️ Tipos de Navegação Implementados

O projeto conta com a estruturação de:
* **Stack Navigation:** Para fluxos lineares e empilhamento de telas.
* **Bottom Tabs:** Navegação por abas inferiores para acesso rápido.
* **Drawer Navigation:** Menu lateral deslizante para navegação global.

---

**Stack:**

### 1° envio: Navegação via Hook (`useNavigation`)
Implementação utilizando o hook moderno da biblioteca, permitindo que componentes funcionais realizem a navegação sem depender de props diretas.
> **Vantagem:** Maior desacoplamento de componentes e facilidade em componentes profundamente aninhados.

### 2°envio: Navegação via Propriedade (`props`)
Uso da propriedade `navigation` injetada automaticamente pelo Navigator nas telas registradas.
> **Vantagem:** Abordagem clássica e direta para telas principais da rota.

### 3° Envio: Tipagem Flexível e Parâmetros
Implementação de **TypeScript** para garantir segurança no fluxo de dados entre telas.
> **Passagem de Parâmetros:** Demonstração de como enviar e receber dados (ex: IDs, nomes ou objetos) através da rota.

> **Tipagem:** Definição de tipos para as rotas, evitando erros de navegação para telas inexistentes ou envio de parâmetros incorretos.


---

**Bottom Tabs:**
### 4° Envio: Navegação por Abas (`Bottom Tabs`)
Implementação da navegação inferior, ideal para a organização das funcionalidades principais do app.
> **UX/UI:** Melhor acessibilidade e troca rápida de contexto entre telas principais.

> **Customização:** Configuração de ícones e estilos para a barra de abas.

---

