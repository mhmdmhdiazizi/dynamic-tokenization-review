# 1. Dynamic Tokenization

## 1.1. Definition: 
Dynamic tokenization refers to methods that adaptively chunk input data based on its content, structure, or patterns. Dynamic tokenizers adjust token boundaries to optimize model performance or efficiency.

## 1.2. Key Characteristics:
1. **Content-aware**: Token boundaries depend on semantic, syntactic, or visual features.
2. **Learned or adaptive**: Often integrated into the model architecture (e.g., adaptive patching, learned segmentation).
3. **Modality-specific implementations**:
- NLP: Variable-length subwords or learned tokenizers.
- Vision: Adaptive patching or region proposals based on saliency.
- Audio/Time-series: Dynamic windowing or frame selection based on signal characteristics.


# 2. Static Tokenization

## 2.1. Definition:
Static tokenization involves a predefined vocabulary (NLP) or fixed-sized regular windowing (for Vision and Time series).

## 2.2. Key Characteristics:
1. **Input-independent**: Token boundaries are fixed and repeatable.
2. **Preprocessing step**: Often applied before model training.
3. **Modality-specific implementations**:
- NLP: Byte Pair Encoding (BPE), WordPiece, whitespace-based tokenization.
- Vision: Fixed-size image patches (e.g., 16×16 in ViT).
- Audio/Time-series: Uniform frame slicing or fixed windowing.


# 3. Primary Research Question

- Across natural language, vision, audio, and general time-series data, how do dynamic tokenization techniques compare to static tokenization methods in terms of model performance, computational efficiency, and their underlying conceptual principles?
# 4. Secondary Research Questions

1.	**Performance & Efficiency**:
- What is the reported impact of dynamic tokenization methods (e.g., adaptive patching) on standard performance metrics (e.g., GLUE scores, ImageNet accuracy, WER) compared to their static counterparts?
- How do these dynamic methods affect the computational trade-offs, such as inference speed, memory usage, and training cost?
2.	**Conceptual Arguments**:
- What theoretical motivations (e.g., data adaptivity, inductive bias reduction) support dynamic tokenization?
- What are the limitations or challenges of implementing dynamic tokenization (increased training complexity or instability)?
3.	**Generalizability and Cross-Modality**:
- How well do specific dynamic tokenization methods generalize when applied to different tasks, domains, or languages within their original modality?
- To what extent have dynamic tokenization strategies proposed for one modality (e.g., NLP) been successfully adapted or expanded to other modalities (e.g., vision, audio)?
- Can shared algorithmic principles (e.g., "adaptive segmentation) be identified across the different modalities?
- How are these shared principles implemented differently to accommodate the unique characteristics of text, images, or audio data?

# 5. Complementary Research Questions

1.	How do tokenization-free models redefine or bypass the tokenization paradigm, and what implications does this have for modality-agnostic representation learning?

# 6. Search Keywords

## Column 1: Dynamism in tokens

### Dynamism Group

- Dynamic*
- Adaptive
- Flexible
- Dependent (represents content-dependent, input-dependent, length-dependent, data-dependent, content-dependent, ...)

### Tokens Group

- Token*
- Patch*
- Embedding*
- Chunk*

### Combined Group

- Tokenization-free
- Compress* token*
- Compress* for token*

## Column 2: Models

- Sequence model*
- Large * model*
- Transformer
- Foundation* model*


## Column 3: Domain

### NLP Group

- Language
- Text*
- Linguistic*
- NLP
- Word*
- Character*
- Byte*

### Vision Group

- Vision
- Image*
- Video
- Visual
- Spatio*

### Time series Group

- Time*
- Temporal
- Signal
- Electro\*gra\*
- Bio*al
- Sensor*
- Sequence
- Audio
- Speech
- Acoustic
- Music*



# 7. Inclusion and Exclusion Criteria

## 7.1. Inclusion Criteria (A paper must meet these to be included):
- The study must explicitly discuss or evaluate a method for tokenizing data (text, images, audio, etc.).
- The study must focus on a dynamic, adaptive, or flexible tokenization method.
- The study must be a peer-reviewed paper (conference, journal), or an influential arXiv pre-print with empirical analysis.
- The study must be written in English.
- Publication date after 2017 (to focus on the Transformer era).

## 7.2. Exclusion Criteria (A paper will be excluded if it meets any of these):
- The study only uses standard, static tokenization methods (e.g., standard BPE, fixed patches) without comparing them to a dynamic alternative.
- The study is only proposes methods based on merging the token obtained from standard patch embedding stages.
- The study does not discuss tokenization (e.g., it just mentions the tokenizer used as part of a larger architecture without specifications on the method or its architecure).
- The study is a tutorial, blog post, or non-technical summary.
- The study is a position paper without empirical analysis.

# 8. Search Strategy
To ensure a comprehensive and structured retrieval of relevant literature, our search strategy adopts a combinatorial keyword model grounded in the conceptual taxonomy outlined earlier. Specifically, we form keyword triplets by selecting one term from each of the following three semantic categories: (1) Dynamism in tokens, (2) Models, and (3) Domain. This approach allows us to systematically explore intersections between adaptive tokenization mechanisms and modeling frameworks across modalities.

Each query string is constructed using Boolean logic operators, enabling precise and flexible filtering within academic search engines such as PubMed, IEEE Xplore, and Google Scholar. Example construction:

```
(("dynamic*" OR "adaptive*") 
AND ("token*" OR "patch*") OR "tokenization-free")
AND ("Transformer" OR "LLM")
AND ("vison" OR "NLP")
```

This strategy facilitates the identification of papers that:

- Explicitly discuss adaptive or dynamic tokenization techniques.
- Frame these within either Transformer-based or modern sequence modeling (e.g., HNet) architectures.
- Address modality-specific or cross-modality applications in NLP, vision, audio, or time-series domains.

The systematic combination of terms helps maintain coverage across diverse research communities while respecting domain-specific terminologies. Additional filters (e.g., publication date post-2017, language constraints, peer-reviewed status) will be applied during the screening phase in line with the protocol’s inclusion/exclusion criteria.

# 9. Complementary Keywords:

- Unit*
- Segment*
- Boundar*