# 🖥️ Comandos Técnicos do CMD – Uso em Hardware no Windows

Este documento lista alguns técnicos do **Prompt de Comando (CMD)** voltados para diagnóstico e análise de hardware em sistemas Windows. Útil para técnicos, engenheiros, analistas de TI e desenvolvedores embarcados.

Este documento lista alguns comandos do **Prompt de Comando (CMD)** voltados para a área de hardware, explicando **o que fazem** e **quando podem ser úteis**.

---

## 🔎 `systeminfo`

**O que faz?**  
Exibe informações detalhadas do sistema, como fabricante, modelo, versão do BIOS, quantidade de memória RAM, processador e atualizações instaladas.

**Quando pode ser útil?**  
- Diagnóstico rápido da máquina.  
- Coletar dados para inventário de hardware.  
- Verificar configurações sem precisar abrir fisicamente o computador.

---

## ⚡ `powercfg /batteryreport`

**O que faz?**  
Gera um relatório detalhado sobre o uso da bateria (em laptops), incluindo ciclos de carga, capacidade nominal e desgaste.

**Quando pode ser útil?**  
- Monitorar a saúde da bateria.  
- Identificar perda de desempenho ou autonomia.  
- Avaliar se é necessário substituir a bateria.

---

## 💽 `wmic diskdrive get status`

**O que faz?**  
Mostra o status dos discos rígidos/SSDs conectados. Normalmente exibe **"OK"** quando o disco está saudável.

**Quando pode ser útil?**  
- Diagnosticar possíveis falhas em HD/SSD.  
- Verificação inicial antes de substituição preventiva de hardware.

---

## 🧩 `driverquery`

**O que faz?**  
Lista todos os drivers instalados no sistema, mostrando nome, tipo e data de instalação.

**Quando pode ser útil?**  
- Identificar drivers ausentes ou desatualizados.  
- Resolver conflitos de hardware.  
- Conferir versões antes de atualizar componentes.

---

## 📊 `chkdsk`

**O que faz?**  
Verifica e repara erros no disco rígido/SSD, avaliando integridade do sistema de arquivos e setores defeituosos.

**Quando pode ser útil?**  
- Resolver problemas de inicialização.  
- Recuperar arquivos corrompidos.  
- Prevenir falhas futuras no armazenamento.

---

## 🌐 `ipconfig /all`

**O que faz?**  
Mostra informações completas sobre as interfaces de rede: IP, MAC Address, gateway, DNS e adaptadores físicos.

**Quando pode ser útil?**  
- Diagnóstico de problemas de rede.  
- Obter endereço MAC para controle de acesso.  
- Confirmar se a placa de rede está funcionando corretamente.

---

## 🖥️ `msinfo32`

**O que faz?**  
Abre a ferramenta de **Informações do Sistema**, mostrando detalhes sobre hardware, BIOS, dispositivos, drivers e recursos.

**Quando pode ser útil?**  
- Diagnóstico avançado.  
- Obter dados detalhados para suporte técnico.  
- Conferir configurações sem abrir o gabinete.

---

## 🔧 `dxdiag`

**O que faz?**  
Abre a **Ferramenta de Diagnóstico do DirectX**, que exibe informações sobre CPU, memória, placa de vídeo, som e periféricos.

**Quando pode ser útil?**  
- Testar componentes de vídeo e áudio.  
- Verificar suporte a recursos gráficos.  
- Diagnóstico de problemas em jogos e multimídia.

---

# ✅ Conclusão

Esses comandos ajudam técnicos e usuários a:  
- Obter informações rápidas sobre hardware.  
- Diagnosticar falhas.  
- Monitorar desempenho de componentes.  
- Preparar relatórios de manutenção preventiva.

