# Fichamento do Artigo 1: An Early Detection of Android Malware Using System Calls Based Machine Learning Model

"An Early Detection of Android Malware Using System Calls Based Machine Learning Model." *Proceedings of the 17th International Conference on Availability, Reliability and Security (ARES 2022)*, Viena, Áustria, 2022. DOI: [10.1145/3538969.3544413](https://doi.org/10.1145/3538969.3544413)

## 1. Fichamento de Conteúdo

Este artigo explora um modelo de aprendizado de máquina baseado na análise de chamadas de sistema para a detecção precoce de malware em dispositivos Android. Utilizando traços de chamadas de sistema coletados de aplicativos benignos e maliciosos, os autores desenvolveram um sistema que processa esses traços usando modelos como N-gramas e TF-IDF para extrair características relevantes. O modelo, treinado com algoritmos como Árvore de Decisão, Random Forest e Perceptron Multicamadas, alcançou uma precisão média de 99,34% com uma janela de detecção inicial de 3000 chamadas de sistema. O estudo também apresenta a implementação de um aplicativo Android, baseado em uma arquitetura cliente-servidor, para detectar malware em tempo real, destacando a viabilidade da abordagem para ambientes práticos.

## 2. Fichamento Bibliográfico

- _Sistema de detecção de intrusão baseado em host (HIDS)_: Detecta ataques em dispositivos específicos usando dados de chamadas de sistema (página 2).
- _N-grama e TF-IDF_: Técnicas de processamento de linguagem natural aplicadas para criar características a partir de sequências de chamadas de sistema (página 4).
- _Perceptron Multicamadas (MLP)_: Algoritmo de aprendizado de máquina utilizado para classificação de malware com alta precisão (página 6).
- _Arquitetura cliente-servidor_: Base do aplicativo Android proposto para monitoramento e detecção de malware (página 7).
- _Traço de chamadas de sistema_: Coletado usando ferramentas como _strace_ para distinguir entre apps benignos e maliciosos (página 5).

## 3. Fichamento de Citações

* _"System call analysis is effective for intrusions and malware detection by identifying anomalous behavior."_  
* _"Our Android malware detection system (AMDS) achieved early detection with an average accuracy of 99.34%."_  
* _"To enhance data processing, the collected system call traces were transformed using N-gram and TF-IDF models."_  
* _"The system enables real-time monitoring and detection of malware through an Android app developed on client-server architecture."_  
* _"This model addresses limitations in processing large amounts of system call traces, ensuring quick and accurate malware classification."_  
