# Supported CLI Metadata Types

This list compares metadata types found in Salesforce v60 with the [metadata registry file](./src/registry/metadataRegistry.json) included in this repository.

This repository is used by both the Salesforce CLIs and Salesforce's VSCode Extensions.

Currently, there are 0/0 supported metadata types.
For status on any existing gaps, please search or file an issue in the [Salesforce CLI issues only repo](https://github.com/forcedotcom/cli/issues).
To contribute a new metadata type, please see the [Contributing Metadata Types to the Registry](./contributing/metadata.md)

|Metadata Type|Support|Notes|
|:---|:---|:---|



## Next Release (v61)

> **Note**
> v61 coverage not available at this time

## Additional Types

> The following types are supported by this library but not in the coverage reports for either version.  These are typically
>
> 1. types that have been removed from the metadata API but were supported in previous versions
> 1. types that are available for pilots but not officially part of the metadata API (use with caution)
> 1. types that exist only as a child type of other metadata types
> 1. settings types that are automatically supported

- AccessControlPolicy
- AccountForecastSettings
- AccountingFieldMapping
- AccountingModelConfig
- AccountRelationshipShareRule
- AcctMgrTargetSettings
- ActionableEventOrchDef
- ActionableEventTypeDef
- ActionableListDefinition
- ActionLauncherItemDef
- ActionLinkGroupTemplate
- ActionPlanTemplate
- ActivationPlatform
- ActnblListKeyPrfmIndDef
- AdvAccountForecastSet
- AdvAcctForecastDimSource
- AdvAcctForecastPeriodGroup
- AIApplication
- AIApplicationConfig
- AIAssistantTemplate
- AIScoringModelDefinition
- AIScoringModelDefVersion
- AIUsecaseDefinition
- AnalyticSnapshot
- AnimationRule
- ApexClass
- ApexComponent
- ApexEmailNotifications
- ApexPage
- ApexTestSuite
- ApexTrigger
- ApplicationRecordTypeConfig
- ApplicationSubtypeDefinition
- AppMenu
- AppointmentAssignmentPolicy
- AppointmentSchedulingPolicy
- ApprovalProcess
- AssessmentQuestion
- AssessmentQuestionSet
- AssignmentRules
- AssignmentRule
- AssistantContextItem
- AssistantDefinition
- AssistantRecommendationType
- AssistantSkillQuickAction
- AssistantSkillSobjectAction
- AssistantVersion
- Audience
- AuraDefinitionBundle
- AuthProvider
- AutoResponseRules
- AutoResponseRule
- BatchCalcJobDefinition
- BatchProcessJobDefinition
- BenefitAction
- BlacklistedConsumer
- BldgEnrgyIntensityCnfg
- Bot
- BotVersion
- BotBlock
- BotTemplate
- BrandingSet
- BriefcaseDefinition
- BusinessProcessFeedbackConfiguration
- BusinessProcessGroup
- BusinessProcessTypeDefinition
- CallCenter
- CallCenterRoutingMap
- CallCoachingMediaProvider
- CallCtrAgentFavTrfrDest
- CampaignInfluenceModel
- CanvasMetadata
- CareBenefitVerifySettings
- CareLimitType
- CareProviderAfflRoleConfig
- CareProviderSearchConfig
- CareRequestConfiguration
- CareSystemFieldMapping
- CaseSubjectParticle
- Certificate
- ChannelLayout
- ChannelObjectLinkingRule
- ChatterExtension
- ClauseCatgConfiguration
- CleanDataService
- CMSConnectSource
- CommandAction
- Community
- CommunityTemplateDefinition
- CommunityThemeDefinition
- ConnectedApp
- ContentAsset
- ContextDefinition
- ConversationChannelDefinition
- ConversationVendorFieldDef
- ConversationVendorInfo
- CorsWhitelistOrigin
- CspTrustedSite
- CustomApplication
- CustomApplicationComponent
- CustomDataType
- CustomExperience
- CustomFeedFilter
- CustomHelpMenuSection
- CustomIndex
- CustomLabels
- CustomLabel
- CustomMetadata
- CustomNotificationType
- CustomObject
- BusinessProcess
- CompactLayout
- CustomField
- FieldSet
- Index
- ListView
- RecordType
- SharingReason
- ValidationRule
- WebLink
- CustomObjectTranslation
- CustomFieldTranslation
- CustomPageWebLink
- CustomPermission
- CustomSite
- CustomTab
- Dashboard
- DashboardFolder
- DataCalcInsightTemplate
- DataCategoryGroup
- DataConnectorIngestApi
- DataConnectorS3
- DataKitObjectTemplate
- DataPackageKitDefinition
- DataPackageKitObject
- DataPipeline
- DataSource
- DataSourceBundleDefinition
- DataSourceObject
- DataSourceTenant
- DataSrcDataModelFieldMap
- DataStreamDefinition
- DataStreamTemplate
- DataWeaveResource
- DecisionMatrixDefinition
- DecisionMatrixDefinitionVersion
- DecisionTable
- DecisionTableDatasetLink
- DelegateGroup
- DigitalExperienceBundle
- DigitalExperience
- DigitalExperienceConfig
- DisclosureDefinition
- DisclosureDefinitionVersion
- DisclosureType
- DiscoveryAIModel
- DiscoveryGoal
- DiscoveryStory
- Document
- DocumentCategory
- DocumentCategoryDocumentType
- DocumentFolder
- DocumentGenerationSetting
- DocumentType
- DuplicateRule
- DynamicTrigger
- EclairGeoData
- EmailFolder
- EmailServicesFunction
- EmailTemplate
- EmailTemplateFolder
- EmbeddedServiceBranding
- EmbeddedServiceConfig
- EmbeddedServiceFieldService
- EmbeddedServiceFlowConfig
- EmbeddedServiceLiveAgent
- EmbeddedServiceMenuSettings
- EnablementMeasureDefinition
- EnablementProgramDefinition
- EntitlementProcess
- EntitlementTemplate
- EntityImplements
- EscalationRules
- EscalationRule
- ESignatureConfig
- ESignatureEnvelopeConfig
- EventDelivery
- EventRelayConfig
- EventSubscription
- EventType
- ExperienceBundle
- ExperiencePropertyTypeBundle
- ExplainabilityActionDefinition
- ExplainabilityActionVersion
- ExplainabilityMsgTemplate
- ExpressionSetDefinition
- ExpressionSetDefinitionVersion
- ExpressionSetMessageToken
- ExpressionSetObjectAlias
- ExtDataTranObjectTemplate
- extDataTranFieldTemplate
- ExternalAIModel
- ExternalClientApplication
- ExternalCredential
- ExternalDataConnector
- ExternalDataSource
- ExternalServiceRegistration
- ExtlClntAppConfigurablePolicies
- ExtlClntAppGlobalOauthSettings
- ExtlClntAppMobileConfigurablePolicies
- ExtlClntAppMobileSettings
- ExtlClntAppNotificationSettings
- ExtlClntAppOauthConfigurablePolicies
- ExtlClntAppOauthSettings
- ExtlClntAppSampleConfigurablePolicies
- ExtlClntAppSampleSettings
- FeatureParameterBoolean
- FeatureParameterDate
- FeatureParameterInteger
- FieldRestrictionRule
- FieldServiceMobileExtension
- FieldSrcTrgtRelationship
- FlexiPage
- Flow
- FlowCategory
- FlowDefinition
- FlowTest
- ForecastingFilter
- ForecastingFilterCondition
- ForecastingSourceDefinition
- ForecastingType
- ForecastingTypeSource
- Form
- FormSection
- FuelType
- FuelTypeSustnUom
- FunctionReference
- FundraisingConfig
- GatewayProviderPaymentMethodType
- GenAiPromptTemplate
- GenAiPromptTemplateActv
- GlobalPicklist
- GlobalValueSet
- GlobalValueSetTranslation
- Group
- HomePageComponent
- HomePageLayout
- Icon
- IdentityVerificationProcDef
- IframeWhiteListUrlSettings
- InboundCertificate
- InboundNetworkConnection
- IndustriesManufacturingSettings
- InsightType
- InstalledPackage
- IntegrationHubSettings
- IntegrationHubSettingsType
- IntegrationProviderDef
- InternalDataConnector
- InternalOrganization
- IPAddressRange
- KeywordList
- Layout
- LeadConvertSettings
- Letterhead
- LicenseDefinition
- LightningBolt
- LightningComponentBundle
- LightningExperienceTheme
- LightningMessageChannel
- LightningOnboardingConfig
- LiveChatAgentConfig
- LiveChatButton
- LiveChatDeployment
- LiveChatSensitiveDataRule
- LocationUse
- LoyaltyProgramSetup
- ManagedContentType
- ManagedEventSubscription
- ManagedTopics
- ManagedTopic
- MarketingAppExtension
- MarketingResourceType
- MarketSegmentDefinition
- MatchingRules
- MatchingRule
- MessagingChannel
- MfgProgramTemplate
- MilestoneType
- MktCalcInsightObjectDef
- MktDataTranObject
- MktDataTranField
- MLDataDefinition
- MlDomain
- MlModelArtifact
- MlModelConnection
- MlModelSchema
- MLPredictionDefinition
- MLRecommendationDefinition
- MobileApplicationDetail
- MobileSecurityAssignment
- MobileSecurityPolicy
- MobileSecurityPolicySet
- MobSecurityCertPinConfig
- ModerationRule
- MutingPermissionSet
- MyDomainDiscoverableLogin
- NamedCredential
- NavigationMenu
- Network
- NetworkBranding
- NotificationTypeConfig
- OauthCustomScope
- OauthTokenExchangeHandler
- ObjectHierarchyRelationship
- ObjectSourceTargetMap
- OcrSampleDocument
- OcrTemplate
- OmniDataTransform
- OmniExtTrackingDef
- OmniIntegrationProcedure
- OmniInteractionAccessConfig
- OmniInteractionConfig
- OmniScript
- OmniSupervisorConfig
- OmniTrackingGroup
- OmniUiCard
- Orchestration
- OrchestrationContext
- OutboundNetworkConnection
- ParticipantRole
- PathAssistant
- PaymentGatewayProvider
- PermissionSet
- PermissionSetGroup
- PermissionSetLicenseDefinition
- PersonAccountOwnerPowerUser
- PipelineInspMetricConfig
- PlatformCachePartition
- PlatformEventChannel
- PlatformEventChannelMember
- PlatformEventSubscriberConfig
- Portal
- PostTemplate
- PresenceDeclineReason
- PresenceUserConfig
- PricingActionParameters
- PricingRecipe
- ProcessFlowMigration
- ProductAttributeSet
- ProductSpecificationTypeDefinition
- Profile
- ProfilePasswordPolicy
- ProfileSessionSetting
- Prompt
- Queue
- QueueRoutingConfig
- QuickAction
- RecommendationStrategy
- RecordActionDeployment
- RecordAggregationDefinition
- RecordAlertCategory
- RecordAlertDataSource
- RedirectWhitelistUrl
- RegisteredExternalService
- RelationshipGraphDefinition
- RemoteSiteSetting
- Report
- ReportFolder
- ReportType
- RestrictionRule
- Role
- SalesAgreementSettings
- SamlSsoConfig
- SchedulingObjective
- SchedulingRule
- Scontrol
- ScoreCategory
- SearchableObjDataSyncInfo
- SearchCriteriaConfiguration
- ServiceAISetupDefinition
- ServiceAISetupField
- ServiceChannel
- ServicePresenceStatus
- ServiceProcess
- Settings
- SharingRules
- SharingCriteriaRule
- SharingGuestRule
- SharingOwnerRule
- SharingTerritoryRule
- SharingSet
- SiteDotCom
- Skill
- SkillType
- SlackApp
- StandardValueSet
- StandardValueSetTranslation
- StaticResource
- StnryAssetEnvSrcCnfg
- StreamingAppDataConnector
- SustainabilityUom
- SustnUomConversion
- SvcCatalogCategory
- SvcCatalogFilterCondition
- SvcCatalogFilterCriteria
- SvcCatalogFulfillmentFlow
- SvcCatalogItemDef
- SvcCatalogItemDefFiltrCrit
- SynonymDictionary
- Territory
- Territory2
- Territory2Model
- Territory2Rule
- Territory2Type
- TimelineObjectDefinition
- TimeSheetTemplate
- TopicsForObjects
- TransactionSecurityPolicy
- Translations
- UIObjectRelationConfig
- UiPlugin
- UiViewDefinition
- UserAccessPolicy
- UserAuthCertificate
- UserCriteria
- UserProfileSearchScope
- UserProvisioningConfig
- VehicleAssetEmssnSrcCnfg
- ViewDefinition
- VisualizationPlugin
- WaveApplication
- WaveComponent
- WaveDashboard
- WaveDataflow
- WaveDataset
- WaveLens
- WaveRecipe
- WaveTemplateBundle
- WaveXmd
- WebStoreBundle
- WebStoreTemplate
- Workflow
- WorkflowAlert
- WorkflowFieldUpdate
- WorkflowKnowledgePublish
- WorkflowOutboundMessage
- WorkflowRule
- WorkflowSend
- WorkflowTask
- WorkSkillRouting
- WorkSkillRoutingAttribute
- XOrgHub
