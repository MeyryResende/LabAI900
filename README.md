# LabAI900

## Criando um modelo de previsão com seus devidos pontos de extremidade configurados

1 - Acesse o portal Azure com sua credencial. [https://portal.azure.com](https://portal.azure.com)

2 - Na tela inicial clique no Workspace criado na aula de LAB

## Bora para o modelo 😃

## JSON
{
    "runId": "mslearn-bike-automl",
    "runUuid": "dd15a16b-9f8d-4b04-933a-7ab24afe2337",
    "parentRunUuid": null,
    "rootRunUuid": "dd15a16b-9f8d-4b04-933a-7ab24afe2337",
    "target": "Serverless",
    "status": "Completed",
    "parentRunId": null,
    "dataContainerId": "dcid.mslearn-bike-automl",
    "createdTimeUtc": "2024-02-21T01:59:50.6534391+00:00",
    "startTimeUtc": "2024-02-21T02:00:05.223Z",
    "endTimeUtc": "2024-02-21T02:09:51.671Z",
    "error": null,
    "warnings": null,
    "tags": {
        "_aml_system_automl_mltable_data_json": "{\"Type\":\"MLTable\",\"TrainData\":{\"Uri\":\"azureml://locations/eastus/workspaces/451e8db7-15a3-4db5-afe8-ae6d784a2c6b/data/alugueldebicicletas/versions/1\",\"ResolvedUri\":null,\"AssetId\":null},\"TestData\":null,\"ValidData\":null}",
        "model_explain_run": "best_run",
        "_aml_system_automl_run_workspace_id": "451e8db7-15a3-4db5-afe8-ae6d784a2c6b",
        "_aml_system_azureml.automlComponent": "AutoML",
        "pipeline_id_000": "faf12f74cf9bbd358ca5525682c5030d36f7be7c;b76be6b5846772ee1128c4d415381c1e9fed455e;__AutoML_Ensemble__",
        "score_000": "0.09357675586470318;0.10163301699114019;0.08924339099536134",
        "predicted_cost_000": "0;0.5;0",
        "fit_time_000": "0.076642;0.020359;1",
        "training_percent_000": "100;100;100",
        "iteration_000": "0;1;2",
        "run_preprocessor_000": "MaxAbsScaler;MaxAbsScaler;",
        "run_algorithm_000": "LightGBM;RandomForest;VotingEnsemble",
        "automl_best_child_run_id": "mslearn-bike-automl_2"
    },
    "properties": {
        "num_iterations": "3",
        "training_type": "TrainFull",
        "acquisition_function": "EI",
        "primary_metric": "normalized_root_mean_squared_error",
        "train_split": "0",
        "acquisition_parameter": "0",
        "num_cross_validation": "",
        "target": "Serverless",
        "AMLSettingsJsonString": "{\"is_subgraph_orchestration\":false,\"is_automode\":true,\"path\":\"./sample_projects/\",\"subscription_id\":\"dc941d22-6a53-47e1-a46d-cd6fcf05b516\",\"resource_group\":\"LABAI-900_MR1\",\"workspace_name\":\"laboratorioai900\",\"iterations\":3,\"primary_metric\":\"normalized_root_mean_squared_error\",\"task_type\":\"regression\",\"IsImageTask\":false,\"IsTextDNNTask\":false,\"validation_size\":0.1,\"n_cross_validations\":null,\"preprocess\":true,\"is_timeseries\":false,\"time_column_name\":null,\"grain_column_names\":null,\"max_cores_per_iteration\":-1,\"max_concurrent_iterations\":3,\"max_nodes\":3,\"iteration_timeout_minutes\":15,\"enforce_time_on_windows\":false,\"experiment_timeout_minutes\":15,\"exit_score\":\"NaN\",\"experiment_exit_score\":\"NaN\",\"whitelist_models\":[\"RandomForest\",\"LightGBM\"],\"blacklist_models\":null,\"blacklist_algos\":[\"TensorFlowDNN\",\"TensorFlowLinearRegressor\"],\"auto_blacklist\":false,\"blacklist_samples_reached\":false,\"exclude_nan_labels\":false,\"verbosity\":20,\"model_explainability\":false,\"enable_onnx_compatible_models\":false,\"enable_feature_sweeping\":false,\"send_telemetry\":true,\"enable_early_stopping\":true,\"early_stopping_n_iters\":20,\"distributed_dnn_max_node_check\":false,\"enable_distributed_featurization\":true,\"enable_distributed_dnn_training\":true,\"enable_distributed_dnn_training_ort_ds\":false,\"ensemble_iterations\":3,\"enable_tf\":false,\"enable_cache\":false,\"enable_subsampling\":false,\"metric_operation\":\"minimize\",\"enable_streaming\":false,\"use_incremental_learning_override\":false,\"force_streaming\":false,\"enable_dnn\":false,\"is_gpu_tmp\":false,\"enable_run_restructure\":false,\"featurization\":\"auto\",\"vm_type\":\"Standard_DS3_v2\",\"vm_priority\":\"dedicated\",\"label_column_name\":\"rentals\",\"weight_column_name\":null,\"miro_flight\":\"default\",\"many_models\":false,\"many_models_process_count_per_node\":0,\"automl_many_models_scenario\":null,\"enable_batch_run\":true,\"save_mlflow\":true,\"track_child_runs\":true,\"test_include_predictions_only\":false,\"enable_mltable_quick_profile\":\"True\",\"has_multiple_series\":false,\"_enable_future_regressors\":false,\"enable_ensembling\":true,\"enable_stack_ensembling\":false,\"ensemble_download_models_timeout_sec\":300.0,\"stack_meta_learner_train_percentage\":0.2}",
        "DataPrepJsonString": null,
        "EnableSubsampling": "False",
        "runTemplate": "AutoML",
        "azureml.runsource": "automl",
        "_aml_internal_automl_best_rai": "False",
        "ClientType": "Mfe",
        "_aml_system_scenario_identification": "Remote.Parent",
        "PlatformVersion": "DPV2",
        "environment_cpu_name": "AzureML-AutoML",
        "environment_cpu_label": "prod",
        "environment_gpu_name": "AzureML-AutoML-GPU",
        "environment_gpu_label": "prod",
        "root_attribution": "automl",
        "attribution": "AutoML",
        "Orchestrator": "AutoML",
        "CancelUri": "https://eastus.api.azureml.ms/jasmine/v1.0/subscriptions/dc941d22-6a53-47e1-a46d-cd6fcf05b516/resourceGroups/LABAI-900_MR1/providers/Microsoft.MachineLearningServices/workspaces/laboratorioai900/experimentids/9306bea1-ec96-46b5-8b5e-0b83c9bbae73/cancel/mslearn-bike-automl",
        "mltable_data_json": "{\"Type\":\"MLTable\",\"TrainData\":{\"Uri\":\"azureml://locations/eastus/workspaces/451e8db7-15a3-4db5-afe8-ae6d784a2c6b/data/alugueldebicicletas/versions/1\",\"ResolvedUri\":\"azureml://locations/eastus/workspaces/451e8db7-15a3-4db5-afe8-ae6d784a2c6b/data/alugueldebicicletas/versions/1\",\"AssetId\":\"azureml://locations/eastus/workspaces/451e8db7-15a3-4db5-afe8-ae6d784a2c6b/data/alugueldebicicletas/versions/1\"},\"TestData\":null,\"ValidData\":null}",
        "ClientSdkVersion": null,
        "snapshotId": "00000000-0000-0000-0000-000000000000",
        "SetupRunId": "mslearn-bike-automl_setup",
        "SetupRunContainerId": "dcid.mslearn-bike-automl_setup",
        "FeaturizationRunJsonPath": "featurizer_container.json",
        "FeaturizationRunId": "mslearn-bike-automl_featurize",
        "ProblemInfoJsonString": "{\"dataset_num_categorical\": 0, \"is_sparse\": true, \"subsampling\": false, \"has_extra_col\": true, \"dataset_classes\": 552, \"dataset_features\": 64, \"dataset_samples\": 657, \"single_frequency_class_detected\": false}"
    },
    "parameters": {},
    "services": {},
    "inputDatasets": null,
    "outputDatasets": [],
    "runDefinition": null,
    "logFiles": {},
    "jobCost": {
        "chargedCpuCoreSeconds": null,
        "chargedCpuMemoryMegabyteSeconds": null,
        "chargedGpuSeconds": null,
        "chargedNodeUtilizationSeconds": null
    },
    "revision": 13,
    "runTypeV2": {
        "orchestrator": "AutoML",
        "traits": [
            "automl",
            "Remote.Parent"
        ],
        "attribution": null,
        "computeType": null
    },
    "settings": {},
    "computeRequest": null,
    "compute": {
        "target": "Serverless",
        "targetType": "AmlCompute",
        "vmSize": "Standard_DS3_v2",
        "instanceType": "Standard_DS3_v2",
        "instanceCount": 1,
        "gpuCount": null,
        "priority": "Dedicated",
        "region": null,
        "armId": null,
        "properties": null
    },
    "createdBy": {
        "userObjectId": "7e7e1760-0299-4506-817f-fa6d07925dea",
        "userPuId": "1003200356BEB205",
        "userIdp": "live.com",
        "userAltSecId": "1:live.com:000340016BF17002",
        "userIss": "https://sts.windows.net/a8009e76-6dc5-41cb-a0db-74558a2f88cb/",
        "userTenantId": "a8009e76-6dc5-41cb-a0db-74558a2f88cb",
        "userName": "Meyry Resende",
        "upn": null
    },
    "computeDuration": "00:09:46.4473338",
    "effectiveStartTimeUtc": null,
    "runNumber": 1708480790,
    "rootRunId": "mslearn-bike-automl",
    "experimentId": "9306bea1-ec96-46b5-8b5e-0b83c9bbae73",
    "userId": "7e7e1760-0299-4506-817f-fa6d07925dea",
    "statusRevision": 3,
    "currentComputeTime": null,
    "lastStartTimeUtc": null,
    "lastModifiedBy": {
        "userObjectId": "7e7e1760-0299-4506-817f-fa6d07925dea",
        "userPuId": "1003200356BEB205",
        "userIdp": "live.com",
        "userAltSecId": "1:live.com:000340016BF17002",
        "userIss": "https://sts.windows.net/a8009e76-6dc5-41cb-a0db-74558a2f88cb/",
        "userTenantId": "a8009e76-6dc5-41cb-a0db-74558a2f88cb",
        "userName": "Meyry Resende",
        "upn": null
    },
    "lastModifiedUtc": "2024-02-21T02:09:51.2820329+00:00",
    "duration": "00:09:46.4473338",
    "inputs": {
        "training_data": {
            "assetId": "azureml://locations/eastus/workspaces/451e8db7-15a3-4db5-afe8-ae6d784a2c6b/data/alugueldebicicletas/versions/1",
            "type": "MLTable"
        }
    },
    "outputs": {
        "best_model": {
            "assetId": "azureml://locations/eastus/workspaces/451e8db7-15a3-4db5-afe8-ae6d784a2c6b/models/azureml_mslearn-bike-automl_2_output_mlflow_log_model_971140291/versions/1",
            "type": "MLFlowModel"
        }
    },
    "currentAttemptId": 1
}
