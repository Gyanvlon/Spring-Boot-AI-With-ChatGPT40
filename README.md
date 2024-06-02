# Spring AI Multimodal + GPT-4o

## Spring AI

Multimodality refers to a model’s ability to simultaneously understand and process information from various sources, including text, images, audio, and other data formats. Presently, the OpenAI gpt-4-visual-preview and gpt-4o models offers multimodal support. If you want to learn more about multi-modal support
in Spring AI please visit the [documentation](https://docs.spring.io/spring-ai/reference/1.0-SNAPSHOT/api/chat/openai-chat.html#_multimodal).

### Getting Started

To get started you will need register for an [OpenAI account](https://platform.openai.com/apps) and obtain an API Key. Once you have an
api key you can set the following property in `application.properties`. In this example I have extracted the key to an environment variable.You will also
need to set the model to `gpt-4o`.

```properties
spring.ai.openai.api-key=${OPENAI_API_KEY}
spring.ai.openai.chat.options.model=gpt-4o
```

The examples in this repository require at least `1.0.0-SNAPSHOT`. To enable snapshots you will need to add the `spring-snapshots` repository declaration. 

### Chat Modal

### Image Modal

### Audio Modal