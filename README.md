# 📱 Calculadora de IMC

Um aplicativo Android moderno e intuitivo para calcular o Índice de Massa Corporal (IMC), desenvolvido em Kotlin com Jetpack Compose.

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)

## 📋 Sobre o Projeto

A Calculadora de IMC é um aplicativo que permite aos usuários calcular rapidamente seu Índice de Massa Corporal e obter informações sobre sua classificação de peso. O app oferece uma interface moderna e educativa, fornecendo não apenas o resultado do cálculo, mas também explicações sobre o que é o IMC e sua importância.

## ✨ Funcionalidades

- 🧮 **Cálculo preciso do IMC** - Divisão do peso pela altura ao quadrado
- 📊 **Classificação automática** - Baseada nos padrões da OMS
- 📚 **Informações educativas** - Explicações sobre IMC e sua utilidade
- 🎨 **Interface moderna** - Desenvolvida com Material Design 3
- 🔄 **Função de restart** - Limpar campos rapidamente
- 🌈 **Cores indicativas** - Visual intuitivo para cada classificação
- 📱 **Design responsivo** - Adaptado para diferentes tamanhos de tela

## 📊 Classificações do IMC

| Faixa de IMC | Classificação | Cor do Indicador |
|--------------|---------------|------------------|
| Menor que 18,5 | Abaixo do peso | 🟠 Laranja |
| 18,5 - 24,9 | Peso normal | 🟢 Verde |
| 25,0 - 29,9 | Sobrepeso | 🟠 Laranja |
| 30,0 - 34,9 | Obesidade Grau I | 🔴 Vermelho |
| 35,0 - 39,9 | Obesidade Grau II | 🔴 Vermelho |
| 40,0 ou mais | Obesidade Grau III | 🔴 Vermelho |

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Kotlin
- **UI Framework:** Jetpack Compose
- **Design System:** Material Design 3
- **Minimum SDK:** 24 (Android 7.0)
- **Target SDK:** 36
- **Build Tool:** Gradle Kotlin DSL

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Android Studio Arctic Fox ou superior
- JDK 8 ou superior
- Dispositivo Android ou emulador com API 24+

### Passos para execução

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/CalculadoraIMC.git
   ```

2. **Abra o projeto no Android Studio:**
   - File → Open → Selecione a pasta do projeto

3. **Sincronize as dependências:**
   - Aguarde o Gradle sincronizar automaticamente
   - Ou execute: `./gradlew clean build`

4. **Execute o aplicativo:**
   - Conecte um dispositivo Android ou inicie um emulador
   - Clique em "Run" ou pressione `Shift + F10`

## 📖 Como Usar

1. **Digite seu peso** em quilogramas (kg) no primeiro campo
2. **Digite sua altura** em metros (m) no segundo campo
   - Exemplo: para 1,75m digite "1.75" ou "1,75"
3. **Clique em "Calcular IMC"** para obter o resultado
4. **Visualize o resultado** com a classificação correspondente
5. **Use "Restart"** para limpar os campos e fazer um novo cálculo

### Dicas de uso:
- Use ponto (.) ou vírgula (,) como separador decimal
- A altura deve ser informada em metros (ex: 1.75 para 1,75m)
- O peso deve ser informado em quilogramas

## 🎨 Interface do Usuário

O aplicativo apresenta:

- **Título destacado** com fonte serif elegante
- **Seções informativas expansíveis** sobre IMC
- **Campos de entrada** com validação de dados
- **Botões de ação** com elevação e feedback visual
- **Card de resultado** com informações claras e coloridas
- **Bordas arredondadas** e sombreamento suave

## 🧪 Funcionalidades Técnicas

- **Validação de entrada:** Aceita vírgula e ponto como separadores decimais
- **Tratamento de erros:** Mensagens claras para entradas inválidas
- **Estado reativo:** Interface atualizada em tempo real
- **Composables reutilizáveis:** Código organizado e manutenível

## 📁 Estrutura do Projeto

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/example/calculadoraimc/
│   │   │   ├── MainActivity.kt          # Activity principal
│   │   │   └── ui/theme/               # Tema e cores
│   │   ├── res/                        # Recursos do app
│   │   └── AndroidManifest.xml         # Configurações do app
│   ├── androidTest/                    # Testes instrumentados
│   └── test/                          # Testes unitários
├── build.gradle.kts                   # Configurações de build
└── proguard-rules.pro                 # Regras de ofuscação
```

## 🤝 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request


**⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!**
