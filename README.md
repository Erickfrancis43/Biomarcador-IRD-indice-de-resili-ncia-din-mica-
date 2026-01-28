# Biomarcador-IRD-indice-de-resili-ncia-din-mica-
IRD: Biomarcador preditivo via Lei de Escala da Ação. Monitora PAM/FC para detectar perda de resiliência sistêmica. Antecipa eventos críticos em 67min (Esp. 98.1%). Patente INPI 870260004287. Modelo escalável de baixo custo. 
# IRD - Índice de Resiliência Dinâmica

**Vigilância Clínica Antecipatória Baseada em Leis de Escala**

[![Status](https://img.shields.io/badge/Status-Preprint-blue.svg)]()

## 📌 Sobre o Projeto
O IRD é um biomarcador preditivo original projetado para detectar a perda de resiliência sistêmica antes de colapsos clínicos manifestos. Diferente de escores reativos (como NEWS2), o IRD utiliza o acoplamento dinâmico entre Pressão Arterial Média (PAM) e Frequência Cardíaca (FC) sob a ótica da **Lei de Escala da Ação**.

### Principais Diferenciais:
* **[span_14](start_span)Antecipação:** ~67 minutos de vantagem clínica antes do colapso[span_14](end_span).
* **[span_15](start_span)Precisão:** Redução de 87,6% em alarmes falsos comparado ao NEWS2[span_15](end_span).
* **[span_16](start_span)Simplicidade:** Requer apenas dois sinais vitais universais[span_16](end_span).

## 📊 Resultados de Validação
O modelo foi testado em bases de dados públicas (Pima Indians, CardioTrain, NHANES) e simulações de alta fidelidade ($n=10.000$):

| Métrica | IRD (PHI) | NEWS2 |
| :--- | :---: | :---: |
| Sensibilidade | 99.3% | 99.7% |
| Especificidade | 98.1% | 84.6% |
| F1-Score | 0.958 | 0.754 |
| Lead Time | 67.3 min | 47.4 min |

## 📂 Estrutura do Repositório
* `/docs`: Contém o preprint completo em PDF.
* `/assets`: Imagens dos gráficos e curvas ROC.
* `/src`: (Opcional) Scripts de calibração ou calculadoras simplificadas.

## ⚖️ Propriedade Intelectual
[span_17](start_span)Patente depositada junto ao **INPI sob nº 870260004287**[span_17](end_span). Todos os direitos reservados. Para uso acadêmico, favor citar conforme o arquivo `CITATION.cff`.

## ✉️ Contato
Autor: Erick F. Damasceno Gouveia
