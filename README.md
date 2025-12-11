# 🧠 DFH / SLPI Compliance Examination · Question Set (v1.0)

This file defines the **canonical 150-question exam** for the  
Semantic First-Hop / Deterministic First-Hop (SFH / DFH) protocol.

Every question is designed to be **answerable directly from the DFH / SLPI specification**.

---

## 🧐 Section A — Core Concepts & Philosophy (1–25)

1. In your own words, what is the Semantic First-Hop / Deterministic First-Hop (SFH / DFH) protocol?  
2. What problem does DFH solve that Retrieval-Augmented Generation (RAG) does not?  
3. Explain the phrase: “One file. Ten anchors. Zero dependencies. Pure JSON-LD.”  
4. What is the purpose of placing DFH at https://<domain>/.well-known/stack?  
5. How does DFH relate to DNS in terms of responsibility and function?  
6. Complete: “DNS answers: Where is it? DFH answers: ______?”  
7. Why is DFH a “deterministic first-hop” rather than a heuristic method?  
8. How does DFH reduce or prevent hallucinations in AI systems?  
9. What is the Semantic Layer of the Public Internet (SLPI)?  
10. What does it mean that DFH provides a “public, universal, domain-controlled identity root”?  
11. Describe the Deterministic Grounding Pipeline from DNS to model output.  
12. How is DFH different from placing arbitrary JSON on an arbitrary path?  
13. Why is JSON-LD chosen instead of plain JSON?  
14. Why is DFH decentralized even though DNS roots are centralized?  
15. In what way does DFH function like a “DNS for meaning”?  
16. Why does DFH emphasize zero external dependencies?  
17. What does it mean that DFH expresses intent, while safety layers regulate output?  
18. How could DFH integrate into an AI system’s grounding pipeline?  
19. Why is /.well-known/stack a machine-verifiable identity record?  
20. Explain the difference between semantic grounding and retrieval.  
21. How can DFH improve search engine interpretation of domains?  
22. Why is canonical identity important when aggregating multi-source data?  
23. Why is DFH called the “missing semantic substrate of the web”?  
24. How could DFH strengthen knowledge graph construction?  
25. Why is DFH fully compatible with HTTPS, DNS, and /.well-known paths?

---

## 🧭 Section B — The Ten Anchors: Meaning Layer (26–60)

26. List the five meaning anchors in DFH.  
27. List the five provenance anchors in DFH.  
28. What is the purpose of the /type anchor?  
29. Why should /type use machine-readable IRIs or known vocabularies?  
30. What is the role of the /entity anchor?  
31. Explain the difference between /entity and /url.  
32. Why must /url generally match the origin domain serving the DFH file?  
33. What does /canonical represent?  
34. How is /canonical different from /url?  
35. What is the purpose of the /sitemap anchor?  
36. How does /sitemap act as a first-hop topology for subtopics?  
37. Provide a /type example for a company domain.  
38. Provide a /type example for a dataset domain.  
39. What should a well-formed /entity communicate?  
40. Why must /canonical be self-referential and stable?  
41. What URLs or nodes should be referenced under /sitemap?  
42. How does /sitemap help AI reason about domain scope and structure?  
43. Why should /sitemap reflect logical subtopics rather than every URL?  
44. If a site changes its homepage layout, how does that affect meaning anchors?  
45. When might /url and /canonical differ, and why?  
46. Why should /type avoid ambiguous descriptions like “site” or “page”?  
47. How can /entity help disambiguate similar brands or near-identical names?  
48. Provide an example of a /sitemap entry for a structured blog.  
49. How can /sitemap help AI prioritize crawling or interpretation?  
50. Why is /sitemap considered semantic topology rather than a raw XML sitemap?  
51. How might a DFH /sitemap differ from a traditional sitemap.xml?  
52. How could /type and /entity together describe a non-profit organization?  
53. Why should /url use HTTPS whenever possible?  
54. How do meaning anchors provide deterministic meaning at the domain root?  
55. Why does filling all five meaning anchors reduce ambiguity for AI systems?  
56. Can DFH meaning anchors be implemented on a subdomain? Explain.
