<html lang="en-US">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <img src = "DTE_Bank_wxO.png"
    	width="auto" height="1200"
         alt = "New Watson Assistant Bank" />

</head>

<script>
  window.watsonAssistantChatOptions = {
  integrationID: "f373003d-6da7-4534-b364-5087c739db3c", // The ID of this integration.
  region: "wxo-us-south", // The region your integration is hosted in.
  serviceInstanceID: "4d4a88ee-e3b5-4c8c-8875-8405bca0f08b", // The ID of your service instance.
  orchestrateUIAgentExtensions: false, // If you wish to enable optional UI Agent extensions.
  onLoad: async (instance) => { await instance.render(); }
};
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js";
    document.head.appendChild(t);
  });
</script>

<body></body>

</html>
