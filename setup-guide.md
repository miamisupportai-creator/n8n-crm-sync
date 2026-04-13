# Guia de Setup — CRM Sync Automatizado

## Descripcion
Sincronizacion entre Zoho CRM y HubSpot. Corre cada hora, detecta cambios, transforma datos, y actualiza el CRM destino.

## Pasos
1. Importar `workflow.json` en n8n
2. Configurar credencial de Zoho CRM (OAuth)
3. Configurar credencial de HubSpot (API Key)
4. Reemplazar `${CLIENT_ID}` con el token real
5. Activar el workflow

## Variables Configuradas
| Variable | Valor |
|----------|-------|
| CLIENT_ID | ${CLIENT_ID} |
| CLIENT_NAME | ${CLIENT_NAME} |
| BUDGET | ${BUDGET} |

## Flujo
```
Zoho CRM -> Detectar cambios -> Transformar -> HubSpot
```

## Campos Sincronizados
| Zoho | HubSpot |
|------|---------|
| Full_Name | firstname |
| Email | email |
| Phone | phone |
| Lead_Status | lifecyclestage |

## Soporte
contact@ai50m.com | ai50m.com
