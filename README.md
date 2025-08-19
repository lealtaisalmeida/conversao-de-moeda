# 💱 Conversor de Moedas - Challenge Back End ONE  

Um **conversor de moedas via console** que obtém taxas de câmbio em tempo real por meio da [Exchange Rate API](https://www.exchangerate-api.com/).  
O sistema apresenta um menu interativo, permite realizar conversões entre diferentes moedas e mantém um **histórico de conversões** com registros em log.  

---

## 🚀 Tecnologias Utilizadas  

- **Java 21 (JDK)**  
- **Gson** (para manipulação de JSON)  
- **IDE:** IntelliJ IDEA  
- **API:** [Exchange Rate API](https://www.exchangerate-api.com/)  

---

## ⚙️ Instalação  

### 🔹 Pré-requisitos  
Antes de começar, verifique se você possui:  
- **Java JDK 21** instalado.  
- **Gson** adicionado como dependência (via **Maven**, **Gradle** ou manualmente).  
- Uma variável de ambiente chamada **`API_KEY_EXCHANGE_RATE`** contendo a chave da sua API do *Exchange Rate API*.  

### 🔹 Configuração  
1. Baixe ou clone este repositório.  
2. Instale o **Java JDK 21** no seu sistema.  
3. Adicione a biblioteca **Gson** ao projeto.  
   - Se estiver usando **Maven**, adicione no `pom.xml`:  

   ```xml
   <dependency>
     <groupId>com.google.code.gson</groupId>
     <artifactId>gson</artifactId>
     <version>2.10.1</version>
   </dependency>
