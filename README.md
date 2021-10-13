# OKD4-INSTALL

los yaml son para dar permisos a SA a procesar templates en namespace openshift

oc policy add-role-to-user admin -z pipelineprocesstemplate -n $NAMESPACE
