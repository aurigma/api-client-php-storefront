# # PersonalizationParametersDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**product_type** | [**\Aurigma\Storefront\Model\ProductType**](ProductType.md) | Customer&#39;s Canvas product type. | [optional]
**id** | **int** | Customer&#39;s Canvas product identifier.  May keep reference to &#x60;Product&#x60;, &#x60;Product Specification&#x60;, &#x60;Product Link&#x60; or &#x60;Product Bundle&#x60; (depending on &#x60;Type&#x60; value). | [optional]
**version_id** | **int** | Customer&#39;s Canvas product version identifier.  May keep reference to version of &#x60;Product&#x60;, &#x60;Product Link&#x60; or &#x60;Product Bundle&#x60; (depending on &#x60;Type&#x60; value). | [optional]
**api_gateway_url** | **string** | API Gateway URL address. | [optional]
**design_editor_url** | **string** | Design Editor application URL address. | [optional]
**preflight_url** | **string** | Preflight application URL address. | [optional]
**dynamic_image_url** | **string** | Dynamic Image application URL address. | [optional]
**ui_framework_url** | **string** | Link to UI-Framework bundle. | [optional]
**simple_editor_url** | **string** | Link to Simple Editor bundle. | [optional]
**workflow_elements_url** | **string** | Link to Workflow Elements bundle. | [optional]
**workflow_type** | [**\Aurigma\Storefront\Model\WorkflowType**](WorkflowType.md) | Personalization workflow type. | [optional]
**workflow_content** | **string** | Serialized content of compiled personalization workflow. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
