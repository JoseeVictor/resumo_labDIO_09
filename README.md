# resumo_labDIO_09
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

No estudo realizado, começamos acessando o **Portal de Confiança da Azure**, uma ferramenta essencial para garantir a conformidade e segurança das operações dentro da plataforma. Este portal oferece um conjunto de recursos que auxiliam na **auditoria** de atividades e no monitoramento das práticas de segurança, garantindo que as operações estejam alinhadas com as normas e padrões de compliance.

Em seguida, aprendemos sobre a **criação de bloqueios de recurso a nível de grupo de serviço**. Esses bloqueios são mecanismos que protegem os recursos contra modificações acidentais ou exclusões. Observamos que, ao aplicar um bloqueio a um grupo de recursos, **todos os recursos dentro desse grupo herdam o bloqueio automaticamente**. Isso é útil para proteger grandes conjuntos de recursos de uma só vez.

No entanto, notamos que **ao mover um recurso de um grupo para outro**, ele **perde o bloqueio herdado** do grupo original. Isso ocorre porque os bloqueios aplicados a nível de grupo não são mantidos durante a movimentação. Para evitar que o recurso perca essa proteção, o bloqueio deve ser configurado **diretamente a nível de recurso**, garantindo que ele permaneça protegido independentemente de onde esteja.

Durante a navegação pelo **Azure Purview**, entendemos que essa ferramenta age como um ponto central para a **governança e gestão de dados** na Azure, funcionando como um "switch" de aplicativos. Ela permite que as organizações monitorizem, categorizem e gerenciem seus dados de forma eficaz, garantindo que as informações estejam seguras e em conformidade com as políticas de governança.

Por fim, exploramos também as **políticas no Azure**, que são regras configuradas para aplicar governança em escala nos recursos da nuvem. As políticas permitem definir limites e normas que os recursos devem seguir, assegurando que estejam sempre em conformidade com as diretrizes estabelecidas pela organização.

Esses aprendizados demonstram a importância de utilizar corretamente as ferramentas de controle e governança da Azure para manter a segurança e conformidade dos ambientes em nuvem.
