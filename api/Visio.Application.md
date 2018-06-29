---
title: Application Object (Visio)
keywords: vis_sdr.chm10040
f1_keywords:
- vis_sdr.chm10040
ms.prod: visio
api_name:
- Visio.Application
ms.assetid: 5b3c8939-793f-116f-11b8-1d4170d95a63
ms.date: 06/08/2017
---


# Application Object (Visio)

Represents an instance of Visio. An external program typically creates or retrieves an  **Application** object before it can retrieve other Visio objects from that instance. Use the Microsoft Visual Basic **CreateObject** function or the **New** keyword to run a new instance, or use the **GetObject** function to retrieve an instance that is already running. You can also use the **CreateObject** function with the **InvisibleApp** object to run a new instance that is invisible. Set the value of the **InvisibleApp** object's **Visible** property to **True** to show it.


## Remarks

Use the  **Documents**, **Windows**, and **Addons** properties of an **Application** object to retrieve the **Document**, **Window**, and **Addon** collections of the instance.

Use the  **ActiveDocument**, **ActivePage**, or **ActiveWindow** property to retrieve the currently active **Document**, **Page**, or **Window** object.


 **Note**  Starting with Visio, the Microsoft Office Fluent user interface (UI) replaces the previous system of layered menus, toolbars, and task panes. VBA objects and members that you used to customize the user interface in previous versions of Visio are still available in Visio, but they function differently.

Use the  **BuiltInMenus**, **BuiltInToolbars**, **CustomMenus**, **CustomToolbars**, or **CommandBars** property to access the **Application** object's menus and toolbars.

 **ActiveDocument** is the default property of an **Application** object.


 **Note**  Code in the Microsoft Visual Basic for Applications project of a Visio document can use the Visio global object instead of a Visio  **Application** object to retrieve other objects.

If your Visual Studio solution includes the  **Microsoft.Office.Interop.Visio** reference, this object maps to the following types:


-  **Microsoft.Office.Interop.Visio.ApplicationClass** (to access the **Application** object.)
    
-  **Microsoft.Office.Interop.Visio.ApplicationClass.Application** (to construct the **Application** object.)
    
-  **Microsoft.Office.Interop.Visio.EApplication_Event** (to access events on the **Application** object.
    

## Events



|**Name**|
|:-----|
|[AfterModal](./Visio.Application.AfterModal.md)|
|[AfterRemoveHiddenInformation](./Visio.Application.AfterRemoveHiddenInformation.md)|
|[AfterReplaceShapes](./Visio.application.afterreplaceshapes.md)|
|[AfterResume](./Visio.Application.AfterResume.md)|
|[AfterResumeEvents](./Visio.Application.AfterResumeEvents.md)|
|[AppActivated](./Visio.Application.AppActivated.md)|
|[AppDeactivated](./Visio.Application.AppDeactivated.md)|
|[AppObjActivated](./Visio.Application.AppObjActivated.md)|
|[AppObjDeactivated](./Visio.Application.AppObjDeactivated.md)|
|[BeforeDataRecordsetDelete](./Visio.Application.BeforeDataRecordsetDelete.md)|
|[BeforeDocumentClose](./Visio.Application.BeforeDocumentClose.md)|
|[BeforeDocumentSave](./Visio.Application.BeforeDocumentSave.md)|
|[BeforeDocumentSaveAs](./Visio.Application.BeforeDocumentSaveAs.md)|
|[BeforeMasterDelete](./Visio.Application.BeforeMasterDelete.md)|
|[BeforeModal](./Visio.Application.BeforeModal.md)|
|[BeforePageDelete](./Visio.Application.BeforePageDelete.md)|
|[BeforeQuit](./Visio.Application.BeforeQuit.md)|
|[BeforeReplaceShapes](./Visio.application.beforereplaceshapes.md)|
|[BeforeSelectionDelete](./Visio.Application.BeforeSelectionDelete.md)|
|[BeforeShapeDelete](./Visio.Application.BeforeShapeDelete.md)|
|[BeforeShapeTextEdit](./Visio.Application.BeforeShapeTextEdit.md)|
|[BeforeStyleDelete](./Visio.Application.BeforeStyleDelete.md)|
|[BeforeSuspend](./Visio.Application.BeforeSuspend.md)|
|[BeforeSuspendEvents](./Visio.Application.BeforeSuspendEvents.md)|
|[BeforeWindowClosed](./Visio.Application.BeforeWindowClosed.md)|
|[BeforeWindowPageTurn](./Visio.Application.BeforeWindowPageTurn.md)|
|[BeforeWindowSelDelete](./Visio.Application.BeforeWindowSelDelete.md)|
|[CalloutRelationshipAdded](./Visio.Application.CalloutRelationshipAdded.md)|
|[CalloutRelationshipDeleted](./Visio.Application.CalloutRelationshipDeleted.md)|
|[CellChanged](./Visio.Application.CellChanged.md)|
|[ConnectionsAdded](./Visio.Application.ConnectionsAdded.md)|
|[ConnectionsDeleted](./Visio.Application.ConnectionsDeleted.md)|
|[ContainerRelationshipAdded](./Visio.Application.ContainerRelationshipAdded.md)|
|[ContainerRelationshipDeleted](./Visio.Application.ContainerRelationshipDeleted.md)|
|[ConvertToGroupCanceled](./Visio.Application.ConvertToGroupCanceled.md)|
|[DataRecordsetAdded](./Visio.Application.DataRecordsetAdded.md)|
|[DataRecordsetChanged](./Visio.Application.DataRecordsetChanged.md)|
|[DesignModeEntered](./Visio.Application.DesignModeEntered.md)|
|[DocumentChanged](./Visio.Application.DocumentChanged.md)|
|[DocumentCloseCanceled](./Visio.Application.DocumentCloseCanceled.md)|
|[DocumentCreated](./Visio.Application.DocumentCreated.md)|
|[DocumentOpened](./Visio.Application.DocumentOpened.md)|
|[DocumentSaved](./Visio.Application.DocumentSaved.md)|
|[DocumentSavedAs](./Visio.Application.DocumentSavedAs.md)|
|[EnterScope](./Visio.Application.EnterScope.md)|
|[ExitScope](./Visio.Application.ExitScope.md)|
|[FormulaChanged](./Visio.Application.FormulaChanged.md)|
|[GroupCanceled](./Visio.Application.GroupCanceled.md)|
|[KeyDown](./Visio.Application.KeyDown.md)|
|[KeyPress](./Visio.Application.KeyPress.md)|
|[KeyUp](./Visio.Application.KeyUp.md)|
|[MarkerEvent](./Visio.Application.MarkerEvent.md)|
|[MasterAdded](./Visio.Application.MasterAdded.md)|
|[MasterChanged](./Visio.Application.MasterChanged.md)|
|[MasterDeleteCanceled](./Visio.Application.MasterDeleteCanceled.md)|
|[MouseDown](./Visio.Application.MouseDown.md)|
|[MouseMove](./Visio.Application.MouseMove.md)|
|[MouseUp](./Visio.Application.MouseUp.md)|
|[MustFlushScopeBeginning](./Visio.Application.MustFlushScopeBeginning.md)|
|[MustFlushScopeEnded](./Visio.Application.MustFlushScopeEnded.md)|
|[NoEventsPending](./Visio.Application.NoEventsPending.md)|
|[OnKeystrokeMessageForAddon](./Visio.Application.OnKeystrokeMessageForAddon.md)|
|[PageAdded](./Visio.Application.PageAdded.md)|
|[PageChanged](./Visio.Application.PageChanged.md)|
|[PageDeleteCanceled](./Visio.Application.PageDeleteCanceled.md)|
|[QueryCancelConvertToGroup](./Visio.Application.QueryCancelConvertToGroup.md)|
|[QueryCancelDocumentClose](./Visio.Application.QueryCancelDocumentClose.md)|
|[QueryCancelGroup](./Visio.Application.QueryCancelGroup.md)|
|[QueryCancelMasterDelete](./Visio.Application.QueryCancelMasterDelete.md)|
|[QueryCancelPageDelete](./Visio.Application.QueryCancelPageDelete.md)|
|[QueryCancelQuit](./Visio.Application.QueryCancelQuit.md)|
|[QueryCancelReplaceShapes](./Visio.application.querycancelreplaceshapes.md)|
|[QueryCancelSelectionDelete](./Visio.Application.QueryCancelSelectionDelete.md)|
|[QueryCancelStyleDelete](./Visio.Application.QueryCancelStyleDelete.md)|
|[QueryCancelSuspend](./Visio.Application.QueryCancelSuspend.md)|
|[QueryCancelSuspendEvents](./Visio.Application.QueryCancelSuspendEvents.md)|
|[QueryCancelUngroup](./Visio.Application.QueryCancelUngroup.md)|
|[QueryCancelWindowClose](./Visio.Application.QueryCancelWindowClose.md)|
|[QuitCanceled](./Visio.Application.QuitCanceled.md)|
|[ReplaceShapesCanceled](./Visio.application.replaceshapescanceled.md)|
|[RuleSetValidated](./Visio.Application.RuleSetValidated.md)|
|[RunModeEntered](./Visio.Application.RunModeEntered.md)|
|[SelectionAdded](./Visio.Application.SelectionAdded.md)|
|[SelectionChanged](./Visio.Application.SelectionChanged.md)|
|[SelectionDeleteCanceled](./Visio.Application.SelectionDeleteCanceled.md)|
|[ShapeAdded](./Visio.Application.ShapeAdded.md)|
|[ShapeChanged](./Visio.Application.ShapeChanged.md)|
|[ShapeDataGraphicChanged](./Visio.Application.ShapeDataGraphicChanged.md)|
|[ShapeExitedTextEdit](./Visio.Application.ShapeExitedTextEdit.md)|
|[ShapeLinkAdded](./Visio.Application.ShapeLinkAdded.md)|
|[ShapeLinkDeleted](./Visio.Application.ShapeLinkDeleted.md)|
|[ShapeParentChanged](./Visio.Application.ShapeParentChanged.md)|
|[StyleAdded](./Visio.Application.StyleAdded.md)|
|[StyleChanged](./Visio.Application.StyleChanged.md)|
|[StyleDeleteCanceled](./Visio.Application.StyleDeleteCanceled.md)|
|[SuspendCanceled](./Visio.Application.SuspendCanceled.md)|
|[SuspendEventsCanceled](./Visio.Application.SuspendEventsCanceled.md)|
|[TextChanged](./Visio.Application.TextChanged.md)|
|[UngroupCanceled](./Visio.Application.UngroupCanceled.md)|
|[ViewChanged](./Visio.Application.ViewChanged.md)|
|[VisioIsIdle](./Visio.Application.VisioIsIdle.md)|
|[WindowActivated](./Visio.Application.WindowActivated.md)|
|[WindowChanged](./Visio.Application.WindowChanged.md)|
|[WindowCloseCanceled](./Visio.Application.WindowCloseCanceled.md)|
|[WindowOpened](./Visio.Application.WindowOpened.md)|
|[WindowTurnedToPage](./Visio.Application.WindowTurnedToPage.md)|

## Methods



|**Name**|
|:-----|
|[AddUndoUnit](./Visio.Application.AddUndoUnit.md)|
|[BeginUndoScope](./Visio.Application.BeginUndoScope.md)|
|[ClearCustomMenus](./Visio.Application.ClearCustomMenus.md)|
|[ClearCustomToolbars](./Visio.Application.ClearCustomToolbars.md)|
|[ConvertResult](./Visio.Application.ConvertResult.md)|
|[DoCmd](./Visio.Application.DoCmd.md)|
|[EndUndoScope](./Visio.Application.EndUndoScope.md)|
|[EnumDirectories](./Visio.Application.EnumDirectories.md)|
|[FormatResult](./Visio.Application.FormatResult.md)|
|[FormatResultEx](./Visio.Application.FormatResultEx.md)|
|[GetBuiltInStencilFile](./Visio.Application.GetBuiltInStencilFile.md)|
|[GetCustomStencilFile](./Visio.Application.GetCustomStencilFile.md)|
|[GetPreviewEnabled](./Visio.Application.GetPreviewEnabled.md)|
|[InvokeHelp](./Visio.Application.InvokeHelp.md)|
|[OnComponentEnterState](./Visio.Application.OnComponentEnterState.md)|
|[PurgeUndo](./Visio.Application.PurgeUndo.md)|
|[QueueMarkerEvent](./Visio.Application.QueueMarkerEvent.md)|
|[Quit](./Visio.Application.Quit.md)|
|[Redo](./Visio.Application.Redo.md)|
|[RegisterRibbonX](./Visio.Application.RegisterRibbonX.md)|
|[RenameCurrentScope](./Visio.Application.RenameCurrentScope.md)|
|[SetCustomMenus](./Visio.Application.SetCustomMenus.md)|
|[SetCustomToolbars](./Visio.Application.SetCustomToolbars.md)|
|[SetPreviewEnabled](./Visio.Application.SetPreviewEnabled.md)|
|[Undo](./Visio.Application.Undo.md)|
|[UnregisterRibbonX](./Visio.Application.UnregisterRibbonX.md)|

## Properties



|**Name**|
|:-----|
|[Active](./Visio.Application.Active.md)|
|[ActiveDocument](./Visio.Application.ActiveDocument.md)|
|[ActivePage](./Visio.Application.ActivePage.md)|
|[ActivePrinter](./Visio.Application.ActivePrinter.md)|
|[ActiveWindow](./Visio.Application.ActiveWindow.md)|
|[AddonPaths](./Visio.Application.AddonPaths.md)|
|[Addons](./Visio.Application.Addons.md)|
|[AlertResponse](./Visio.Application.AlertResponse.md)|
|[Application](./Visio.Application.Application.md)|
|[Assistance](./Visio.Application.Assistance.md)|
|[AutoLayout](./Visio.Application.AutoLayout.md)|
|[AutoRecoverInterval](./Visio.Application.AutoRecoverInterval.md)|
|[AvailablePrinters](./Visio.Application.AvailablePrinters.md)|
|[Build](./Visio.Application.Build.md)|
|[BuiltInMenus](./Visio.Application.BuiltInMenus.md)|
|[BuiltInToolbars](./Visio.Application.BuiltInToolbars.md)|
|[COMAddIns](./Visio.Application.COMAddIns.md)|
|[CommandBars](./Visio.Application.CommandBars.md)|
|[CommandLine](./Visio.Application.CommandLine.md)|
|[ConnectorToolDataObject](./Visio.Application.ConnectorToolDataObject.md)|
|[CurrentEdition](./Visio.Application.CurrentEdition.md)|
|[CurrentScope](./Visio.Application.CurrentScope.md)|
|[CustomMenus](./Visio.Application.CustomMenus.md)|
|[CustomMenusFile](./Visio.Application.CustomMenusFile.md)|
|[CustomToolbars](./Visio.Application.CustomToolbars.md)|
|[CustomToolbarsFile](./Visio.Application.CustomToolbarsFile.md)|
|[DataFeaturesEnabled](./Visio.Application.DataFeaturesEnabled.md)|
|[DefaultAngleUnits](./Visio.Application.DefaultAngleUnits.md)|
|[DefaultDurationUnits](./Visio.Application.DefaultDurationUnits.md)|
|[DefaultRectangleDataObject](./Visio.Application.DefaultRectangleDataObject.md)|
|[DefaultTextUnits](./Visio.Application.DefaultTextUnits.md)|
|[DefaultZoomBehavior](./Visio.Application.DefaultZoomBehavior.md)|
|[DeferRecalc](./Visio.Application.DeferRecalc.md)|
|[DeferRelationshipRecalc](./Visio.Application.DeferRelationshipRecalc.md)|
|[DialogFont](./Visio.Application.DialogFont.md)|
|[Documents](./Visio.Application.Documents.md)|
|[DrawingPaths](./Visio.Application.DrawingPaths.md)|
|[EventInfo](./Visio.Application.EventInfo.md)|
|[EventList](./Visio.Application.EventList.md)|
|[EventsEnabled](./Visio.Application.EventsEnabled.md)|
|[FullBuild](./Visio.Application.FullBuild.md)|
|[HelpPaths](./Visio.Application.HelpPaths.md)|
|[InhibitSelectChange](./Visio.Application.InhibitSelectChange.md)|
|[InstanceHandle32](./Visio.Application.InstanceHandle32.md)|
|[InstanceHandle64](./Visio.Application.InstanceHandle64.md)|
|[IsInScope](./Visio.Application.IsInScope.md)|
|[IsUndoingOrRedoing](./Visio.Application.IsUndoingOrRedoing.md)|
|[IsVisio32](./Visio.IsVisio32.md)|
|[Language](./Visio.Application.Language.md)|
|[LanguageHelp](./Visio.Application.LanguageHelp.md)|
|[LanguageSettings](./Visio.Application.LanguageSettings.md)|
|[LiveDynamics](./Visio.Application.LiveDynamics.md)|
|[MyShapesPath](./Visio.Application.MyShapesPath.md)|
|[Name](./Visio.Application.Name.md)|
|[ObjectType](./Visio.Application.ObjectType.md)|
|[OnDataChangeDelay](./Visio.Application.OnDataChangeDelay.md)|
|[Path](./Visio.Application.Path.md)|
|[PersistsEvents](./Visio.Application.PersistsEvents.md)|
|[ProcessID](./Visio.Application.ProcessID.md)|
|[PromptForSummary](./Visio.Application.PromptForSummary.md)|
|[SaveAsWebObject](./Visio.Application.SaveAsWebObject.md)|
|[ScreenUpdating](./Visio.Application.ScreenUpdating.md)|
|[Settings](./Visio.Application.Settings.md)|
|[ShowChanges](./Visio.Application.ShowChanges.md)|
|[ShowProgress](./Visio.Application.ShowProgress.md)|
|[ShowStatusBar](./Visio.Application.ShowStatusBar.md)|
|[ShowToolbar](./Visio.Application.ShowToolbar.md)|
|[StartupPaths](./Visio.Application.StartupPaths.md)|
|[Stat](./Visio.Application.Stat.md)|
|[StencilPaths](./Visio.Application.StencilPaths.md)|
|[TemplatePaths](./Visio.Application.TemplatePaths.md)|
|[TraceFlags](./Visio.Application.TraceFlags.md)|
|[TypelibMajorVersion](./Visio.Application.TypelibMajorVersion.md)|
|[TypelibMinorVersion](./Visio.Application.TypelibMinorVersion.md)|
|[UndoEnabled](./Visio.Application.UndoEnabled.md)|
|[UserName](./Visio.Application.UserName.md)|
|[VBAEnabled](./Visio.Application.VBAEnabled.md)|
|[Vbe](./Visio.Application.Vbe.md)|
|[Version](./Visio.Application.Version.md)|
|[Visible](./Visio.Application.Visible.md)|
|[Window](./Visio.Application.Window.md)|
|[WindowHandle32](./Visio.Application.WindowHandle32.md)|
|[Windows](./Visio.Application.Windows.md)|
