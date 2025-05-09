```mermaid
graph TD
    A[Fuerza sobre Conductores] --> B(Campo Magnético Externo);
    A --> C(Corriente Eléctrica en el Conductor);
    B --> D{Uniforme o No Uniforme};
    C --> E(Magnitud de la Corriente);
    C --> F(Dirección de la Corriente);
    A --> G(Longitud del Conductor dentro del Campo);
    A --> H{Ángulo entre Corriente y Campo};
    subgraph Ley de Lorentz (Caso Conductor Recto)
        direction LR
        I[Fuerza (F)] -- Prop. --> J[Intensidad de Corriente (I)]
        I -- Prop. --> K[Longitud del Conductor (L)]
        I -- Prop. --> L[Campo Magnético (B)]
        I -- Depende de --> M[Ángulo (θ) entre I y B]
        style M fill:#ccf,stroke:#333,stroke-width:2px
        J -- Unidad --> N(Amperios (A))
        K -- Unidad --> O(Metros (m))
        L -- Unidad --> P(Teslas (T))
        I -- Fórmula --> Q[F = I * L * B * sin(θ)]
    end
    style A fill:#f9f,stroke:#333,stroke-width:2px
