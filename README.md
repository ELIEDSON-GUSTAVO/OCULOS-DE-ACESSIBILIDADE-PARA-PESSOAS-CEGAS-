# OCULOS DE ACESSIBILIDADE PARA PESSOAS CEGAS

Resumo do Projeto: Óculos Inteligentes com Detecção de Obstáculos
Objetivo: Criar óculos inteligentes que alertam o usuário sobre obstáculos próximos, proporcionando segurança e assistência para pessoas com deficiência visual ou em ambientes com visibilidade limitada.

Descrição: Os óculos são equipados com um sensor ultrassônico HC-SR04, que detecta objetos a uma distância de até 3 metros. Quando um obstáculo é detectado, um aviso de áudio é transmitido para os fones de ouvido Bluetooth do usuário, alertando sobre a proximidade do objeto.

Componentes Principais:

ESP32: Microcontrolador responsável por processar a entrada do sensor e gerenciar a conexão Bluetooth.
HC-SR04: Sensor ultrassônico para medição de distância.
Fones de Ouvido Bluetooth: Dispositivo de áudio para reproduzir alertas sonoros.
Fonte de Alimentação: Bateria recarregável para mobilidade.
Fluxo de Funcionamento:

Medição de Distância:

O sensor HC-SR04 emite pulsos ultrassônicos que são refletidos por objetos próximos.
O tempo entre o envio e o retorno do pulso é medido para calcular a distância até o obstáculo.
Detecção de Obstáculos:

Se um objeto estiver a 3 metros ou menos, o sistema considera a situação como uma possível colisão.
Transmissão de Áudio:

Um aviso sonoro é enviado via Bluetooth para os fones de ouvido do usuário, informando sobre o obstáculo.
Reprodução de Áudio:

O alerta é emitido em tempo real, permitindo ao usuário tomar ações corretivas para evitar o obstáculo.
Vantagens:

Mobilidade e Segurança: Proporciona maior liberdade de movimento e reduz o risco de colisões em ambientes desconhecidos.
Facilidade de Uso: Configuração intuitiva e uso diário sem a necessidade de interação manual constante.
Conectividade Bluetooth: Compatibilidade com uma ampla gama de fones de ouvido e dispositivos de áudio sem fio.
Desafios Potenciais:

Precisão em Ambientes Ruidosos: Ruídos ambientais podem interferir no reconhecimento de distância.
Vida Útil da Bateria: O consumo de energia deve ser otimizado para garantir longa duração sem recargas frequentes.
Latência no Áudio: A transmissão de áudio Bluetooth deve ser rápida para garantir que os alertas sejam recebidos a tempo.
Possíveis Extensões:

Feedback Tátil: Integração de vibração ou outros feedbacks táteis para complementar os alertas sonoros.
Expansão de Funcionalidades: Adicionar sensores adicionais, como câmeras ou detectores de luz, para aprimorar a percepção do ambiente.
Integração com Aplicativos: Desenvolvimento de aplicativos móveis para personalizar as configurações e alertas do dispositivo.
