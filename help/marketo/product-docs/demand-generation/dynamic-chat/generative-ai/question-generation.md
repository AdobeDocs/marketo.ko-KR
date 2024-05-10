---
description: 질문 생성 - Marketo 문서 - 제품 설명서
title: 질문 생성
hide: true
hidefromtoc: true
feature: Dynamic Chat
source-git-commit: a6745e4a5321000bc1c91ef99c5f265b4c6c5760
workflow-type: tm+mt
source-wordcount: '409'
ht-degree: 0%

---

# 질문 생성 {#question-generation}

모든 작업과 해당 기간 세부 정보(예: 생성 시기, 총 질문 수, 승인 상태 등)를 확인합니다.

## 질문 생성 {#generate-questions}

1. 생성 AI에서 **지원 응답**.

   ![](assets/question-generation-1.png)

1. 클릭 **질문 생성**.

   ![](assets/question-generation-2.png)

1. 작업에 이름을 지정하고 모든 콘텐츠를 추출할 소스 URL(최대 50개)을 입력합니다. 원하는 주제/키워드를 입력하고 키보드에서 Enter 키를 누릅니다. 완료되면 다음을 클릭합니다. **생성**.

   ![](assets/question-generation-3.png)

   >[!IMPORTANT]
   >
   >Marketo Engage허용 목록에 추가하다 가 제공된 URL에서 컨텐츠를 스크랩할 수 있도록 하려면 먼저 몇 개의 IP 주소를 스크랩해야 합니다. [자세한 내용은 아래를 참조하십시오](#ip-addresses-to-allowlist).

1. 콘텐츠에 따라 질문 및 응답 생성에는 최대 30분이 소요될 수 있습니다. 클릭 **확인**.

   ![](assets/question-generation-4.png)

>[!TIP]
>
>페이지의 상태가 실시간으로 업데이트되지 않습니다. &quot;처리 중&quot;에서 &quot;완료&quot;로 언제 변경되는지 보려면 새로 고침을 누르십시오.

![](assets/question-generation-5.png)

## 질문 및 응답 다운로드 {#download-questions-and-responses}

>[!NOTE]
>
>생성된 질문과 응답은 [응답 라이브러리](/help/marketo/product-docs/demand-generation/dynamic-chat/generative-ai/response-library.md).

1. 원하는 작업을 찾아 이름 옆에 있는 다운로드 아이콘을 클릭합니다.

   ![](assets/question-generation-6.png)

1. 브라우저에서 다운로드 폴더를 찾아 파일을 선택합니다. 브라우저에 따라 다르게 보일 수 있습니다.

   ![](assets/question-generation-7.png)

1. Excel 파일에서, **작업 세부 정보** 질문 및/또는 응답을 추가/편집하는 방법에 대한 지침을 포함하여 작업에 대한 다양한 세부 정보를 표시합니다.

   ![](assets/question-generation-8.png)

   >[!NOTE]
   >
   >질문 및/또는 응답을 일괄 편집하기로 결정한 경우 [여기에서 다시 업로드하는 방법을 알아봅니다.](/help/marketo/product-docs/demand-generation/dynamic-chat/generative-ai/response-library.md).

1. 다음 **Q&amp;R** 탭에는 생성된 질문 및 응답을 포함한 추가 세부 정보가 제공됩니다.

   ![](assets/question-generation-9.png)

## IP 주소 허용 목록 {#ip-addresses-to-allowlist}

질문 및 응답을 생성하는 동안 웹 URL에서 컨텐츠를 추출하려면 웹 팀에서 아래의 모든 IP 주소를 허용 목록에추가된으로 제공했는지 확인하십시오.

<table width="150">
  <tr>
    <td>20.167.0.149</td>
  </tr>
  <tr>
    <td>20.248.129.111</td>
  </tr>
  <tr>
    <td>20.167.0.146</td>
  </tr>
  <tr>
    <td>20.167.0.205</td>
  </tr>
  <tr>
    <td>20.248.135.80</td>
  </tr>
  <tr>
    <td>20.92.173.115</td>
  </tr>
  <tr>
    <td>20.167.0.195</td>
  </tr>
  <tr>
    <td>20.248.128.31</td>
  </tr>
  <tr>
    <td>20.167.1.48</td>
  </tr>
  <tr>
    <td>20.167.1.63</td>
  </tr>
  <tr>
    <td>20.167.1.92</td>
  </tr>
  <tr>
    <td>20.167.1.155</td>
  </tr>
  <tr>
    <td>20.248.135.132</td>
  </tr>
  <tr>
    <td>20.248.135.108</td>
  </tr>
  <tr>
    <td>20.248.134.140</td>
  </tr>
  <tr>
    <td>20.167.1.242</td>
  </tr>
  <tr>
    <td>20.167.0.198</td>
  </tr>
  <tr>
    <td>20.248.133.185</td>
  </tr>
  <tr>
    <td>20.248.134.190</td>
  </tr>
  <tr>
    <td>20.167.1.254</td>
  </tr>
  <tr>
    <td>20.248.128.118</td>
  </tr>
  <tr>
    <td>20.248.131.252</td>
  </tr>
  <tr>
    <td>20.167.0.188</td>
  </tr>
  <tr>
    <td>20.167.0.201</td>
  </tr>
  <tr>
    <td>20.211.64.11</td>
  </tr>
  <tr>
    <td>20.76.243.87</td>
  </tr>
  <tr>
    <td>20.76.244.212</td>
  </tr>
  <tr>
    <td>20.76.245.48</td>
  </tr>
  <tr>
    <td>20.76.245.76</td>
  </tr>
  <tr>
    <td>20.76.246.63</td>
  </tr>
  <tr>
    <td>20.76.246.146</td>
  </tr>
  <tr>
    <td>20.76.246.248</td>
  </tr>
  <tr>
    <td>20.76.247.92</td>
  </tr>
  <tr>
    <td>20.76.247.134</td>
  </tr>
  <tr>
    <td>20.76.247.244</td>
  </tr>
  <tr>
    <td>20.93.168.10</td>
  </tr>
  <tr>
    <td>20.93.168.44</td>
  </tr>
  <tr>
    <td>20.93.168.137</td>
  </tr>
  <tr>
    <td>20.93.169.20</td>
  </tr>
  <tr>
    <td>20.93.169.115</td>
  </tr>
  <tr>
    <td>20.93.169.214</td>
  </tr>
  <tr>
    <td>20.93.170.130</td>
  </tr>
  <tr>
    <td>20.93.170.138</td>
  </tr>
  <tr>
    <td>20.93.170.149</td>
  </tr>
  <tr>
    <td>20.93.172.63</td>
  </tr>
  <tr>
    <td>20.93.173.217</td>
  </tr>
  <tr>
    <td>20.93.173.243</td>
  </tr>
  <tr>
    <td>20.93.174.120</td>
  </tr>
  <tr>
    <td>20.93.174.159</td>
  </tr>
  <tr>
    <td>20.105.224.16</td>
  </tr>
  <tr>
    <td>20.10.235.102</td>
  </tr>
  <tr>
    <td>20.10.235.103</td>
  </tr>
  <tr>
    <td>20.10.235.143</td>
  </tr>
  <tr>
    <td>20.10.235.146</td>
  </tr>
  <tr>
    <td>20.10.235.147</td>
  </tr>
  <tr>
    <td>20.10.235.148</td>
  </tr>
  <tr>
    <td>20.10.235.188</td>
  </tr>
  <tr>
    <td>20.10.235.189</td>
  </tr>
  <tr>
    <td>20.10.235.246</td>
  </tr>
  <tr>
    <td>20.10.235.248</td>
  </tr>
  <tr>
    <td>20.10.235.255</td>
  </tr>
  <tr>
    <td>20.10.236.96</td>
  </tr>
  <tr>
    <td>20.10.236.97</td>
  </tr>
  <tr>
    <td>20.10.236.110</td>
  </tr>
  <tr>
    <td>20.10.236.111</td>
  </tr>
  <tr>
    <td>20.10.235.254</td>
  </tr>
  <tr>
    <td>20.10.236.138</td>
  </tr>
  <tr>
    <td>20.10.236.139</td>
  </tr>
  <tr>
    <td>20.10.236.140</td>
  </tr>
  <tr>
    <td>20.10.236.141</td>
  </tr>
  <tr>
    <td>20.10.236.84</td>
  </tr>
  <tr>
    <td>20.10.236.85</td>
  </tr>
  <tr>
    <td>20.10.236.86</td>
  </tr>
  <tr>
    <td>20.10.236.87</td>
  </tr>
  <tr>
    <td>20.119.144.14</td>
  </tr>
  <tr>
    <td>20.75.41.107</td>
  </tr>
  <tr>
    <td>20.75.43.104</td>
  </tr>
  <tr>
    <td>20.75.43.107</td>
  </tr>
  <tr>
    <td>20.75.43.113</td>
  </tr>
  <tr>
    <td>20.75.43.124</td>
  </tr>
  <tr>
    <td>20.75.43.204</td>
  </tr>
  <tr>
    <td>20.75.43.207</td>
  </tr>
  <tr>
    <td>20.75.43.214</td>
  </tr>
  <tr>
    <td>20.75.43.220</td>
  </tr>
  <tr>
    <td>20.75.44.0</td>
  </tr>
  <tr>
    <td>20.75.44.9</td>
  </tr>
  <tr>
    <td>20.75.44.52</td>
  </tr>
  <tr>
    <td>20.75.44.66</td>
  </tr>
  <tr>
    <td>20.75.44.82</td>
  </tr>
  <tr>
    <td>20.75.44.105</td>
  </tr>
  <tr>
    <td>20.75.44.108</td>
  </tr>
  <tr>
    <td>20.75.44.133</td>
  </tr>
  <tr>
    <td>20.75.44.135</td>
  </tr>
  <tr>
    <td>20.75.44.137</td>
  </tr>
  <tr>
    <td>20.75.44.147</td>
  </tr>
  <tr>
    <td>20.75.44.154</td>
  </tr>
  <tr>
    <td>20.75.44.195</td>
  </tr>
  <tr>
    <td>20.75.44.198</td>
  </tr>
  <tr>
    <td>20.75.45.32</td>
  </tr>
  <tr>
    <td>20.119.136.14</td>
  </tr>
  <tr>
    <td>172.177.93.157</td>
  </tr>
  <tr>
    <td>52.252.22.155</td>
  </tr>
  <tr>
    <td>20.62.18.64</td>
  </tr>
  <tr>
    <td>52.179.234.0</td>
  </tr>
  <tr>
    <td>52.179.234.1</td>
  </tr>
  <tr>
    <td>52.179.237.99</td>
  </tr>
  <tr>
    <td>52.179.237.148</td>
  </tr>
  <tr>
    <td>52.252.23.246</td>
  </tr>
  <tr>
    <td>52.253.64.47</td>
  </tr>
  <tr>
    <td>52.253.64.124</td>
  </tr>
  <tr>
    <td>52.253.64.125</td>
  </tr>
  <tr>
    <td>52.253.65.84</td>
  </tr>
  <tr>
    <td>52.253.65.85</td>
  </tr>
  <tr>
    <td>52.254.103.240</td>
  </tr>
  <tr>
    <td>52.253.65.92</td>
  </tr>
  <tr>
    <td>52.253.65.93</td>
  </tr>
  <tr>
    <td>52.177.89.135</td>
  </tr>
  <tr>
    <td>52.253.69.207</td>
  </tr>
  <tr>
    <td>52.253.69.240</td>
  </tr>
  <tr>
    <td>52.167.19.211</td>
  </tr>
  <tr>
    <td>52.177.147.229</td>
  </tr>
  <tr>
    <td>40.65.238.53</td>
  </tr>
  <tr>
    <td>52.177.147.249</td>
  </tr>
  <tr>
    <td>20.44.83.102</td>
  </tr>
  <tr>
    <td>52.177.148.19</td>
  </tr>
  <tr>
    <td>20.49.97.17</td>
  </tr>
  <tr>
    <td>20.14.171.7</td>
  </tr>
  <tr>
    <td>172.177.93.157</td>
  </tr>
  <tr>
    <td>20.213.91.77</td>
  </tr>
  <tr>
    <td>20.105.150.224</td>
  </tr>
  <tr>
    <td>13.68.17.252</td>
  </tr>
</table>