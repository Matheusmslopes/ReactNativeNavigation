# 📱 React Native Navigation Study
Repositório criado somente para mexer com navegação e configurações de build para desenvolvimento

## 🛠️ Tipos de Navegação Implementados

O projeto conta com a estruturação de:
* **Stack Navigation:** Para fluxos lineares e empilhamento de telas.
* **Bottom Tabs:** Navegação por abas inferiores para acesso rápido.
* **Drawer Navigation:** Menu lateral deslizante para navegação global.

---

Stack: 

### 1° envio: Navegação via Hook (`useNavigation`)
Implementação utilizando o hook moderno da biblioteca, permitindo que componentes funcionais realizem a navegação sem depender de props diretas.
> **Vantagem:** Maior desacoplamento de componentes e facilidade em componentes profundamente aninhados.

### 2°envio: Navegação via Propriedade (`props`)
Uso da propriedade `navigation` injetada automaticamente pelo Navigator nas telas registradas.
> **Vantagem:** Abordagem clássica e direta para telas principais da rota.
