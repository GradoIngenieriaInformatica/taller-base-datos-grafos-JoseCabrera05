MATCH (p:Persona) WHERE NOT (p)-[:AMIGO_DE]-() RETURN p.nombre
