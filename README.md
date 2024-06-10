# UESI
Universal Editor for Structured Information

## Requirements

1. The editor processes data necessry to develop LUT/GUT entities see: ![GUT requirements]()
2. This implementation is a browser JavaScript based implementation that is decoupled from the UI framework via a interface generator.
   * ReactJs, Next.js and Carbon-React are the initial platforms considered
   * The implementation has a static application base implementeing the universal viewer and editor and can discover and dynamically load viewers and specialized editors for a given entity 
4. All possible entities can be creted, modified and inspected via a set of universal structured entity visulalisation and change UI components
5. This editor aims to be for structured data what the text editors are for text editing in most OS-es
6. In this context all data has structure (hance can be edited via this editor) and the only recognized unstructured informatino are:
   * single point in the sky CBM reception data stream
   * pure random data streams
   * encrypted data streams where decryption is not available

