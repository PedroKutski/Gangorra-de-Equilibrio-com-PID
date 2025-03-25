# 🎢 Gangorra Inteligente com Controle Automático

Este projeto explora a automação e o controle de sistemas físicos, aplicando conceitos de feedback, sensores e atuadores para criar uma **gangorra inteligente**! Utilizando um sensor ultrassônico e um motor servo, o sistema ajusta automaticamente a inclinação da gangorra para manter o equilíbrio de um objeto, tornando-se uma aplicação prática e interativa de engenharia de controle. 🚀

---

## 📌 Visão Geral
- **Detecção de posição**: O sensor ultrassônico mede a distância da bolinha sobre a gangorra.
- **Controle dinâmico**: Um microcontrolador processa os dados e envia comandos ao servo motor.
- **Ajustes inteligentes**: O servo motor inclina a gangorra em tempo real para manter o equilíbrio da bolinha.

Essa abordagem pode ser aplicada tanto em projetos educacionais quanto em prototipagem para sistemas de controle industriais! 🏭

---

## 🔬 Desenvolvimento do Sistema
O projeto foi desenvolvido com os seguintes componentes:
- **Microcontrolador** (ESP32, Arduino ou similar) para processar os dados
- **Sensor ultrassônico** para medir a posição da bolinha
- **Servo motor** com rotação de até 120° para ajustar a inclinação
- **Estrutura física** projetada para permitir ajustes finos na estabilidade

A implementação incluiu técnicas de **calibração** e **controle proporcional** para garantir uma resposta rápida e precisa às mudanças de posição da bolinha. 🎯

---

## 🔍 Resultados Obtidos
O objetivo principal era estabilizar uma **bolinha de ping-pong** na gangorra. No entanto, o material da bolinha refletia o som do sensor de forma inconsistente, gerando medições imprecisas. 🔄 Para resolver isso, foi utilizado um **objeto cilíndrico de 2cm de raio**, o que melhorou a detecção e reduziu erros horizontais. ✅

---

## 🚀 Melhorias Futuras
Aqui estão algumas ideias para aprimorar o desempenho do sistema:

🔹 **Substituir o sensor ultrassônico por um sensor a laser** para maior precisão na medição da posição da bolinha. 🟢

🔹 **Reprojetar a estrutura física** da gangorra para um formato em **U**, permitindo uma melhor propagação do som e minimizando interferências nas leituras do sensor ultrassônico. 🛠️

Essas melhorias podem tornar o sistema ainda mais robusto e confiável! 💡

---

## 📜 Licença
Este projeto é de código aberto e está licenciado sob a **MIT License**. Sinta-se à vontade para explorar, modificar e aprimorar! 🎉

