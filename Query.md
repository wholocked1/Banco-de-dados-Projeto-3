Query 1
MATCH p=()-[:FEZ]->(:Disciplina) RETURN p;
Query 2
MATCH p=()-[:Ministrou]->() RETURN p;
Query 3
MATCH(A:Aluno{formado:TRUE}) RETURN A;
Query 4
MATCH p=()-[:CHEFIADO_POR]->() RETURN p;
Query 5
MATCH (a:Aluno)-[f:FEZ]->(t:TCC)<-[o:ORIENTOU]-(p:Professor) RETURN a,t,p,f,o;
