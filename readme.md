# Spectr UI — минимальная документация

Автоматически сгенерировано по файлу `spectr-ui-components.mjs` (собранный бандл UI-кита `@spectr-ui/components`).

**Общие сведения**

- Целевой Angular: **21.1.6**; все компоненты — standalone (или standalone-совместимые).
- Зависимости: `@angular/forms`, `@angular/cdk` (drag-drop, observers, collections), `ngx-mask`, `@ng-web-apis/common`, `@ng-web-apis/resize-observer`, `@ng-web-apis/intersection-observer`, а также пакеты экосистемы `@spectr-ui/core`, `@spectr-ui/helpers`, `@spectr-ui/i18n`, `@spectr-ui/theme`, `@spectr-ui/icons`.
- Описания взяты из JSDoc-комментариев, сохранённых в бандле. Пустое описание — комментарий в исходниках отсутствовал.

## Компоненты

Всего: **127**.

| Класс | Селектор | Входы | Описание (JSDoc) |
|---|---|---|---|
| SpectrAccordionComponent | spectr-accordion | onlyOneExpanded | — |
| SpectrAccordionItemComponent | spectr-accordion-item | icon, iconButtonLeft, isExpanded, title, disabled | — |
| SpectrAvatarComponent | spectr-avatar | appearance, description, shape, size, src, userName | — |
| SpectrAvatarGroupComponent | spectr-avatar-group | size, strokeColor | — |
| SpectrBadgeComponent | spectr-badge | size, appearance, status, backgroundColor, color | — |
| SpectrBannerComponent | spectr-banner | title, description, type, showCloseButton, status, size, link, leftButton, rightButton | — |
| SpectrBreadcrumbsComponent | spectr-breadcrumbs | size, breadcrumbs | — |
| SpectrButtonComponent | button[spectrButton], button[spectrIconButton], a[spectrButton], a[spectrIconButton] | hasIndicator, indicatorStatus, indicatorOutlineColor, size, icon, iconRight, appearance, appearanceType, disab… | — |
| SpectrCalendarComponent | spectr-calendar | month, value, disabledItemHandler, min, max, daysWithStatus, minViewedMonth, maxViewedMonth, hoveredItem, show… | — |
| SpectrCalendarMonthComponent | spectr-calendar-month | value, year, disabledItemHandler, min, max, monthsWithStatus | — |
| SpectrCalendarRangeComponent | spectr-calendar-range | defaultViewedMonth, disabledItemHandler, items, min, max, minLength, maxLength, daysWithStatus, value | — |
| SpectrCalendarYearComponent | spectr-calendar-year | value, initialItem, min, max, disabledItemHandler, yearsWithStatus, hideButtons | — |
| SpectrCardComponent | spectr-card | shadow | — |
| SpectrCheckboxComponent | spectr-checkbox | indeterminate | — |
| SpectrChipsComponent | spectr-chips | size, chips, deletable, singleLine, hintCanShow, hintDirection | — |
| SpectrChipsFilterComponent | spectr-chips-filter | titleIconName, titleText, isBinary, activeLogicalOperator, activeDataProps, dataContent, isDropDownOpen | — |
| SpectrChipsItemComponent | spectr-chips-item | disabled, selected, deletable, hintCanShow, hintText, hintDirection | — |
| SpectrColumnDropListComponent | spectr-column-drop-list | columns, translations, isLastColumnShown | — |
| SpectrColumnSettingsComponent | spectr-column-settings | settings, defaultSettings, stickySettings, headerSettings | — |
| SpectrConfirmPopupContainerComponent | spectr-confirm-popup-container | — | — |
| SpectrCounterComponent | spectr-counter | class, maxValue, status, value | — |
| SpectrCronCarouselComponent | spectr-cron-carousel | content, value | — |
| SpectrCronComponent | spectr-cron | cronTitle, value, disabled, autoSubmit, hidePeriod, hideResult, showHumanReadable, resetButton, period, select… | — |
| SpectrCronDayComponent | spectr-cron-day | specifiedList | — |
| SpectrCronHourComponent | spectr-cron-hour | specifiedList | — |
| SpectrCronMinuteComponent | spectr-cron-minute | specifiedList | — |
| SpectrCronMonthComponent | spectr-cron-month | specifiedList | — |
| SpectrCronScheduleComponent | spectr-cron-schedule | items, selected | — |
| SpectrCronSecondComponent | spectr-cron-second | specifiedList | — |
| SpectrCronYearComponent | spectr-cron-year | specifiedList | — |
| SpectrDataListComponent | spectr-data-list | defaultStyle, iconOff, minHeight, maxHeight, content, scroll | — |
| SpectrDataListWrapperComponent | spectr-data-list-wrapper | defaultStyle, iconOff, minHeight, maxHeight, scroll | — |
| SpectrDialogComponent | spectr-dialog | context, close | — |
| SpectrDialogConfirmComponent | spectr-confirm-dialog | context, close | — |
| SpectrDividerComponent | spectr-divider | type | — |
| SpectrDropdownHostComponent | spectr-dropdown-host | content, spectrDropdownHostId, spectrDropdownCustomContext, delay, canOpen, closeByEsc, closeOnOutsideClick, s… | — |
| SpectrErrorPageComponent | spectr-error-page | code, title | — |
| SpectrExpandComponent | spectr-expand | isLoading, expanded | — |
| SpectrFileUploadComponent | spectr-file-upload | accept, multiple, maxFileSize, maxFilesCount, disabled, progress, files | — |
| SpectrGridComponent | spectr-grid | cols, rows | — |
| SpectrGridItemComponent | spectr-grid-item | colPos, rowPos | — |
| SpectrHeaderComponent | spectr-header | systemName, pageName, logo, userName, userPosition, userIcon, userAvatarAppearance, userAvatarShape, backArrow… | — |
| SpectrHeaderDropdownComponent | spectr-header-dropdown | data, currentScreenIdx | — |
| SpectrHintContainerComponent | spectr-hint-container | id, content, context, hintTheme | — |
| SpectrIndicatorComponent | spectr-indicator | type, size, color, status | — |
| SpectrInputBlockComponent | div[spectrInput] | — | — |
| SpectrInputCarouselAuxiliaryLeftComponent | spectr-input-carousel-auxiliary-left | carousel | — |
| SpectrInputCarouselAuxiliaryRightComponent | spectr-input-carousel-auxiliary-right | carousel | — |
| SpectrInputCarouselComponent | spectr-input-carousel | carouselContent, lightMode | — |
| SpectrInputDateMultiComponent | spectr-input-date-multi | items, currentIdx | — |
| SpectrInputIconButtonComponent | button[spectrInputIconButton] | size, spectrInputIconButton, interactive, disabled, type | — |
| SpectrInputLayoutComponent | spectr-input-layout | label, size, status, clearButton, hideClearButtonHint, border, position, forceClear, readOnly | — |
| SpectrInputLayoutDateComponent | spectr-input-layout-date | min, placeholder, max, disabledItemHandler, defaultActiveYearMonth, extraButtonInjector | — |
| SpectrInputLayoutDateRangeComponent | spectr-input-layout-date-range | defaultViewedMonth, disabledItemHandler, minLength, maxLength, placeholder, items, min, max | — |
| SpectrInputLayoutDateRelativeComponent | spectr-input-layout-date-relative | placeholder, canOpen, extraButtonInjector | — |
| SpectrInputLayoutDateTimeComponent | spectr-input-layout-date-time | timeItems, placeholder, extraButtonInjector, min, max, timeStrict, disabledItemHandler, defaultActiveYearMonth… | — |
| SpectrInputLayoutDateTimeRangeComponent | spectr-input-layout-date-time-range | disabledItemHandler, defaultViewedMonth, items, placeholder, min, max, timeStrict, minLength, maxLength, timeM… | — |
| SpectrInputLayoutMonthComponent | spectr-input-layout-month | min, max, extraButtonInjector, placeholder, disabledItemHandler | — |
| SpectrInputLayoutMonthRangeComponent | spectr-input-layout-month-range | placeholder, min, max, disabledItemHandler, extraButtonInjector | — |
| SpectrInputLayoutTimeComponent | spectr-input-layout-time | placeholder, disabledItemHandler, items, itemSize, strict, mode, extraButtonInjector | — |
| SpectrInputMultiSelectComponent | spectr-input-multi-select | transformer, items, dropdownScroll, dropdownStyles, dropdownClasses, icon, selectAllItem, searchable, isChipsD… | — |
| SpectrInputNumberComponent | input[spectrInputNumber], input[type=number][spectrInput] | placeholder, title, min, max, precision, step | — |
| SpectrInputNumberDefaultControlsComponent | spectr-input-number-auxiliary-controls | inputNumber | — |
| SpectrInputPasswordDefaultControlComponent | spectr-input-password-auxiliary-control | inputPassword | — |
| SpectrInputStatusSubtextComponent | spectr-input-status-subtext | — | — |
| SpectrInputTextComponent | input[spectrInput]:not([type=number]), textarea[spectrInput], input[spectrInputPassword] | disabled, placeholder, required, value | — |
| SpectrInputTreeMultiSelectComponent | spectr-input-tree-multi-select | icon, placeholder, isChipsDeletable | — |
| SpectrInputTreeSelectComponent | spectr-input-tree-select | placeholder, icon | — |
| SpectrListingItemComponent | spectr-listing-item | disabled, selected | — |
| SpectrLoaderComponent | spectr-loader | size, inheritColor, overlay, textContent, showLoader | — |
| SpectrNavigationComponent | spectr-navigation | data, spectrTreeController, activeElement | — |
| SpectrOldSwitcherComponent | spectr-old-switcher | size | — |
| SpectrOldSwitcherItemComponent | spectr-old-switcher-item | icon, value | — |
| SpectrOverlayComponent | spectr-overlay | content | — |
| SpectrPageTabComponent | spectr-page-tab | activeTabTopBorderColor, counterOptions, closeIcon, content, count, disabled, icon | — |
| SpectrPageTabsComponent | spectr-page-tabs | size, canOpen, activeTabIndex, isDropdownButtonDisabled | — |
| SpectrPaginatorComponent | spectr-paginator | paginatorType, textOnPage, leftButtonLabel, rightButtonLabel, moreButtonLabel, totalRecords, pageLinkSize, sho… | — |
| SpectrPanelComponent | spectr-panel | size, withBackButton, header, subheader, icon | — |
| SpectrPrimitiveCalendarComponent | spectr-primitive-calendar | month, disabledItemHandler, value, daysWithStatus, hoveredItem, showAdjacent | — |
| SpectrPrimitiveCalendarRangeComponent | spectr-primitive-calendar-range | disabledItemHandler, defaultViewedMonthFirst, defaultViewedMonthSecond, min, max, daysWithStatus, value | — |
| SpectrPrimitiveMonthPickerComponent | spectr-primitive-month-picker | value, currentYear, initialItem, min, max, disabledItemHandler, rangeState, intervalSupport | — |
| SpectrPrimitiveSpinButtonComponent | spectr-primitive-spin-button | disabled, mode, leftDisabled, rightDisabled | — |
| SpectrPrimitiveYearMonthPaginationComponent | spectr-primitive-year-month-pagination | value, hideButtons, min, max, monthActive, yearActive, step | — |
| SpectrPrimitiveYearPickerComponent | spectr-primitive-year-picker | value, initialItem, min, max, disabledItemHandler, rangeState, yearsWithStatus, intervalSupport, itemsPerRow, … | — |
| SpectrProgressBarComponent | progress[spectrProgressBar] | color, trackColor, size | — |
| SpectrProgressCircleComponent | spectr-progress-circle | value, max, color, trackColor, size | — |
| SpectrProgressLabelComponent | label[spectrProgressLabel] | — | — |
| SpectrProgressSegmentedComponent | spectr-progress-segmented | value, max, size, colors | — |
| SpectrRadioButtonComponent | spectr-radio-button | size, value, name, label, disabled | — |
| SpectrScrollControlsComponent | spectr-scroll-controls | — | — |
| SpectrScrollbarComponent | spectr-scrollbar | visibility | — |
| SpectrSelectInputComponent | spectr-input-select | spectrHintDirection, spectrHintCanShow, items, dropdownScroll, dropdownStyles, dropdownClasses, searchable, ic… | — |
| SpectrSidebarComponent | spectr-sidebar | context, close | — |
| SpectrSliderCnobComponent | spectr-slider-cnob | index, value, showValueOn, disabled | — |
| SpectrSliderComponent | spectr-slider | min, max, step, orientation, range, showMinMax, showValue, cnobValuePosition | — |
| SpectrSpinnerComponent | spectr-spinner | size, inheritColor, textContent | — |
| SpectrSplitButtonComponent | spectr-split-button | size, icon, appearance, appearanceType, disabled, showLoader | — |
| SpectrSplitterAreaComponent | spectr-splitter-area | size, minSize | — |
| SpectrSplitterComponent | spectr-splitter | orientation | — |
| SpectrSplitterGutterComponent | spectr-splitter-gutter | areaBefore, areaAfter, orientation, order | — |
| SpectrSplitterGutterDefaultComponent | spectr-splitter-gutter-default | orientation | — |
| SpectrStepperComponent | spectr-stepper | title, currentStep, vertical, stepsSize | — |
| SpectrStepperSelectorComponent | spectr-stepper-selector | steps, currentStep, vertical | — |
| SpectrSwitcherComponent | spectr-switcher | size | — |
| SpectrSwitcherItemComponent | spectr-switcher-item | icon, value | — |
| SpectrTabComponent | spectr-tab | — | — |
| SpectrTabsComponent | spectr-tabs | fullWidth | — |
| SpectrTbodyComponent | [spectrTbody]  | data, heading, open | — |
| SpectrTdComponent | th[spectrTd], td[spectrTd] | status, colspan | — |
| SpectrThComponent | th[spectrTh] | sorter, resizable, sortable | — |
| SpectrThGroupComponent | tr[spectrThGroup] | columns | — |
| SpectrToastContainerComponent | spectr-toast-container | containerId, position | — |
| SpectrToggleButtonComponent | spectr-toggle-button | appearance, status, disabled, icon, iconRight, isIconButton, size | — |
| SpectrToggleComponent | spectr-toggle | singleColor, iconOn, iconOff, showLoader, size | — |
| SpectrTooltipContainerComponent | spectr-tooltip-container | — | — |
| SpectrTrComponent | tr[spectrTr] | status, columns, active | — |
| SpectrTreeButtonComponent | spectr-tree-button | icon, open, manualChange, removeIcon, visibilityIcon, isSelected, iconOpen, iconClose, level, size, factor | — |
| SpectrTreeComponent | spectr-tree[value] | value, usePaddingIndent, content | — |
| SpectrTreeItemComponent | spectr-tree-item | usePaddingIndent, active | — |
| SpectrTreeItemContentComponent | spectr-tree-item-content | — | — |
| SpectrTreeMultiSelectItemComponent | spectr-input-tree-multi-select-item | — | — |
| SpectrTreeSelectDataListWrapperComponent | spectr-input-tree-select-data-list-wrapper | projectedDataListDirective, parentDropdownHost | — |
| SpectrTreeSelectItemComponent | spectr-input-tree-select-item | — | — |
| SpectrWidgetComponent | spectr-widget | header, title, icons | — |
| SpectrWrapperComponent | spectr-wrapper | disabled, readOnly, pseudoState, hovered, pressed, focused, invalid, appearance | — |
| ToastComponent | spectr-toast-single | — | — |
| ToastWrapperComponent | spectr-toast-wrapper | ref | — |

## Директивы

Всего: **119**.

| Класс | Селектор | Входы | Описание (JSDoc) |
|---|---|---|---|
| AbstractSpectrAutofocusHandler | — | — | — |
| AbstractSpectrControl | — | readOnly, val, pseudoInvalid | — |
| AbstractSpectrController | — | — | — |
| AbstractSpectrInteractive | — | pseudoHovered, pseudoPressed, pseudoFocused, focusable, pseudoState | — |
| AccordionToolsDirective | [spectrAccordionTools] | — | — |
| DefaultInputInvalidTextClass | — | control | — |
| InputInvalidTextBaseClass | — | — | — |
| PolymorphOutletDirective | ng-template[polymorphOutlet] | polymorphOutlet, polymorphOutletInjector, polymorphOutletContext | — |
| PolymorphTemplate | ng-template[polymorph] | polymorph | — |
| SpectrAbstractTabBase | — | icon, content, count, counterOptions, disabled | — |
| SpectrAbstractTabsBase | — | activeTabIndex, canOpen, isDropdownButtonDisabled, size | — |
| SpectrAccordionContentDirective | [spectrAccordionContent] | — | — |
| SpectrAutoFocusDirective | [spectrAutoFocus] | autoFocus | — |
| SpectrAutoResizeDirective | [spectrAutoResize] | spectrAutoResize, autoResizeMode, autoResizeOn | — |
| SpectrBreadcrumbDirective | ng-template[spectrBreadcrumb] | — | — |
| SpectrCellDirective | [spectrCell] | spectrCell | — |
| SpectrCheckedDirective | input[spectrChecked], input[spectrCheckedChange] | spectrChecked | — |
| SpectrChipsIdentityMatcherDirective | spectr-chips[identityMatcher] | — | — |
| SpectrChipsStringifyDirective | spectr-chips[stringify] | — | — |
| SpectrConfirmPopupDirective | [spectrConfirmPopup]:not(ng-container) | size, spectrConfirmPopupTitle, confirmButton, supportButton, cancelButton | — |
| SpectrCounterDirective | [spectrCounter] | counterStatus, counterPosition, spectrCounter, counterMaxValue, counterOutlineCo… | — |
| SpectrDataListDirective | ng-template[spectrDataList] | — | — |
| SpectrDefaultAutofocusHandler | — | — | — |
| SpectrDropdownControllerDirective | [spectrDropdownMinHeight], [spectrDropdownMaxHeight], [spectrDropdownAlign], [spectrDropdownLimitWidth] | spectrDropdownMinHeight, spectrDropdownAlign, spectrDropdownLimitWidth, spectrDr… | — |
| SpectrDropdownHostControlDirective | [spectrDropdownHostControl] | enabled | — |
| SpectrDropdownHostDirective | [spectrDropdownHost] | — | — |
| SpectrDropdownTriggerClickDirective | spectr-dropdown-host[dropdownTrigger=\, spectr-dropdown-host[dropdownTrigger= | dropdownTriggerElement, dropdownDisabled | — |
| SpectrDropdownZoneDirective | [spectrEventZone]:not(ng-container), [spectrEventZoneChange]:not(ng-container), [spectrEventZoneParent]:not(ng-container) | spectrEventZoneParent, spectrEventZoneHost | — |
| SpectrDroppableDirective | [spectrDroppableDropped], [spectrDroppableDragOverChange] | — | — |
| SpectrElementReadyDirective | [spectrElementReady] | interval, checker | — |
| SpectrExpandContentDirective | [spectrExpandContent] | — | — |
| SpectrFocusTrapDirective | [spectrFocusTrap] | — | — |
| SpectrFocusVisibleDirective | [spectrFocusVisibleChange] | — | — |
| SpectrFocusableDirective | [spectrFocusable] | spectrFocusable | — |
| SpectrFocusedDirective | [spectrFocusedChange] | — | — |
| SpectrHeadDirective | [spectrHead] | spectrHead | — |
| SpectrHintDirective | [spectrHint]:not(ng-container) | spectrAutoReposition, spectrHintDirection, spectrHintId, spectrHintTheme, spectr… | — |
| SpectrHintOnOverflowDirective | [spectrHintOnOverflow]:not(ng-container) | spectrHintOnOverflowEl | — |
| SpectrHoveredDirective | [spectrHoveredChange] | — | — |
| SpectrInputAllowedSymbolsDirective | [spectrInputAllowedSymbols] | spectrInputAllowedSymbols | — |
| SpectrInputControl | — | — | — |
| SpectrInputCorrectorDirective | [spectrInputCorrector] | spectrInputCorrector, needCorrect | — |
| SpectrInputHintDirective | input[spectrHintDirection], input[spectrHintCanShow] | spectrHintDirection, spectrHintCanShow | — |
| SpectrInputInZoneDirective | input[spectrInputInZone] | idx, maxSize | — |
| SpectrInputLayoutBottomDirective | ng-template[spectrInputLayoutBottom] | — | — |
| SpectrInputLayoutDateRelativeDirective | spectr-input-layout-date-relative[ngModel], spectr-input-layout-date-relative[formControl], spectr-input-layout-date-relative[formControlName] | — | — |
| SpectrInputLayoutInBodyDirective | ng-template[spectrInputLayoutInBody] | — | — |
| SpectrInputLayoutLeftDirective | ng-template[spectrInputLayoutLeft] | — | — |
| SpectrInputLayoutRightDirective | ng-template[spectrInputLayoutRight] | — | — |
| SpectrInputLayoutSubtextDirective | ng-template[spectrInputLayoutSubtext] | — | — |
| SpectrInputNativeValueDirective | input[spectrInputNativeValue] | spectrInputNativeValue, needChange | — |
| SpectrInputNgControl | — | — | — |
| SpectrInputNumberAuxiliaryControlDirective | [spectrInputNumberAuxiliaryControl] | spectrInputNumberAuxiliaryControl, inputNumber | — |
| SpectrInputPasswordDirective | input[spectrInputPassword] | — | — |
| SpectrInputSelectDataListDirective | ng-template[spectrInputSelectDataList] | — | — |
| SpectrInputSelectOptionDirective | [spectrInputSelectOption] | value | — |
| SpectrInputStatusTextDirective | [spectrInputStatusText] | enable, status | — |
| SpectrInputTreeMultiSelectCheckboxDirective | spectr-input-tree-multi-select[checkboxPosition] | checkboxPosition | — |
| SpectrInputZoneDirective | [spectrInputZone] | — | — |
| SpectrIosAutofocusHandler | — | — | — |
| SpectrLifecycleDirective | [spectrLifecycle], [spectrAfterViewInit], [spectrAfterContentInit], [spectrOnInit], [spectrOnDestroy] | — | — |
| SpectrMutationObserveDirective | [spectrMutationObserver] | spectrMutationObserverConfig, spectrMutationObserverHost | — |
| SpectrOldSwitcherItemsDirective | [spectrOldSwitcherItems] | switchers | — |
| SpectrOldSwitcherTypeDirective | [spectrOldSwitcherType] | type | — |
| SpectrOverscrollDirective | [spectrOverscroll] | spectrOverscroll | — |
| SpectrPressedDirective | [spectrPressedChange] | — | — |
| SpectrPreventDefaultDirective | [spectrPreventDefault] | — | — |
| SpectrProgressColorSegmentsDirective | progress[spectrProgressBar][spectrProgressColorSegments] | spectrProgressColorSegments | — |
| SpectrRepeatTimesDirective | [spectrRepeatTimes][spectrRepeatTimesOf] | spectrRepeatTimesOf | — |
| SpectrResizedDirective | [spectrResized] | — | — |
| SpectrRowDirective | ng-template[spectrRow] | spectrRowOf, spectrRowGetRowId, spectrRowGetChildren, spectrRowTrackBy | — |
| SpectrScrollIntoViewDirective | [spectrScrollIntoView] | spectrScrollIntoView | — |
| SpectrScrollRefDirective | [spectrScrollRef] | — | — |
| SpectrScrollableDirective | [spectrScrollable] | — | — |
| SpectrScrollbarDirective | [spectrScrollbar] | spectrScrollbar | — |
| SpectrScrollbarWrapperDirective | [spectrScrollbarWrapper] | — | — |
| SpectrShadowDirective | [spectrShadow] | spectrShadow | — |
| SpectrSkeletonDirective | [spectrSkeleton], [spectrSkeletonText], [spectrSkeletonRounded], [spectrSkeletonShort] | spectrSkeletonText, spectrSkeletonRounded, spectrSkeletonShort, spectrSkeleton | — |
| SpectrSortByDirective | table[spectrTable][spectrSortBy] | spectrSortBy | — |
| SpectrSortableDirective | th[spectrTh][spectrSortable] | — | — |
| SpectrSplitterCustomGutterDirective | [spectrSplitterCustomGutter] | size | — |
| SpectrStepperSelectorItemDirective | [spectrStepperSelectorItem] | spectrStepperSelectorItem, disabled | — |
| SpectrStepperStepDirective | [spectrStepperStep] | spectrStepperStep, title, status, disabled | — |
| SpectrStickyDirective | [spectrStickyLeft], [spectrStickyRight], [spectrStickyTop], [spectrStickyBottom] | spectrStickyLeft, spectrStickyRight, spectrStickyTop, spectrStickyBottom, spectr… | — |
| SpectrStickyRelativeDirective | [spectrStickyRelative] | — | — |
| SpectrStopPropagationDirective | [spectrStopPropagation] | — | — |
| SpectrSumDirective | button[spectrButton][sum], a[spectrButton][sum] | sum | — |
| SpectrSwitcherControlDirective | [spectrSwitcherControl] | — | — |
| SpectrSwitcherFullWidthDirective | [spectrSwitcherFullWidth] | fullWidth | — |
| SpectrSwitcherItemsDirective | [spectrSwitcherItems] | switchers | — |
| SpectrTableDirective | table[spectrTable] | tableBorderSpacing, columns, size, tableBorderStyle, sort, direction, sorter | — |
| SpectrTableEmptyDirective | ng-template[spectrTableEmpty] | — | — |
| SpectrTableLoadingDirective | ng-template[spectrTableLoading] | — | — |
| SpectrTableRowInitDirective | ng-template[spectrTableRowInit] | context | — |
| SpectrTableTreeLoadingDirective | ng-template[spectrTableTreeLoading] | — | — |
| SpectrTextareaDirective | textarea[spectrInput] | height, resizable | — |
| SpectrTheadDirective | thead[spectrThead] | — | — |
| SpectrTooltipDirective | [spectrTooltip]:not(ng-container) | spectrTooltip, spectrHintTheme | — |
| SpectrTrDirective | tr:not([spectrTr]) | — | — |
| SpectrTreeChildrenDirective | spectr-tree[childrenHandler] | childrenHandler | — |
| SpectrTreeControllerDirective | [spectrTreeController][map] | spectrTreeController, map | — |
| SpectrTreeItemControllerDirective | [spectrTreeController]:not([map]) | spectrTreeController | — |
| SpectrTreeMultiSelectItemDirective | ng-template[spectrInputTreeMultiSelectItem] | spectrInputTreeMultiSelectItem | — |
| SpectrTreeMultiSelectSearchDirective | [spectrInputTreeMultiSelectSearch] | searchable, searchMatcher, searchMapper, searchFilter, searchDebounce, searchPla… | — |
| SpectrTreeMultiSelectSelectedDirective | [spectrInputTreeMultiSelectSelected] | value | — |
| SpectrTreeNodeDirective | spectr-tree-item[spectrTreeNode] | spectrTreeNode | — |
| SpectrTreeSelectEmptyTextDirective | spectrInputTreeSelectEmptyText | emptyListTemplate | — |
| SpectrTreeSelectGetChildrenDirective | [spectrInputTreeSelectGetChildren] | getChildren | — |
| SpectrTreeSelectIdentityMatcherDirective | [spectrInputTreeSelectIdentityMatcher] | identityMatcher | — |
| SpectrTreeSelectIsOpenedDirective | [spectrInputTreeSelectIsOpened] | isOpened | — |
| SpectrTreeSelectItemDirective | ng-template[spectrInputTreeSelectItem] | spectrInputTreeSelectItem | — |
| SpectrTreeSelectItemsDirective | [spectrInputTreeSelectItems] | items | — |
| SpectrTreeSelectSearchDirective | [spectrInputTreeSelectSearch] | searchable, searchMatcher, searchMapper, searchFilter, searchDebounce, searchPla… | — |
| SpectrTreeSelectSearchLabelDirective | spectrInputTreeSelectSearchLabel | searchLabel | — |
| SpectrTreeSelectSelectedDirective | [spectrInputTreeSelectSelected] | value | — |
| SpectrTreeSelectStringifyDirective | [spectrInputTreeSelectStringify] | stringify | — |
| SpectrValueAccessorDirective | [spectrValueAccessor] | — | — |
| SpectrWrappedFormComponent | — | — | — |
| SpectrZoneEventDirective | [spectrZoneEvent] | zoneElement, parentZone, childrenZones, zoneEventName, zoneActive | — |

## Пайпы

Всего: **16**.

| Класс | Имя пайпа | Описание (JSDoc) |
|---|---|---|
| SpaceNumberPipe | spaceNumber | — |
| SpectrCalendarSheetPipe | spectrCalendarSheet | — |
| SpectrColumnIconPipe | spectrColumnIcon | — |
| SpectrCronHumanReadablePipe | spectrCronHumanReadable | — |
| SpectrCronMonthPipe | spectrCronMonth | — |
| SpectrCronWeekPipe | spectrCronWeek | — |
| SpectrFileExtensionPipe | spectrFileExtension | — |
| SpectrFileNamePipe | spectrFileName | — |
| SpectrFileSizePipe | spectrFileSize | — |
| SpectrIconTabsPipe | spectrIconTabs | — |
| SpectrInitialsPipe | spectrInitials | — |
| SpectrMapperPipe | spectrMapper | — |
| SpectrMonthPipe | spectrMonth | — |
| SpectrTableSortPipe | spectrTableSort | — |
| SpectrTimeConstraintsPipe | spectrTimeConstraints | — |
| SpectrUploadStatusPipe | spectrUploadStatus | — |

## Сервисы

Всего: **38**.

| Класс | providedIn | Описание (JSDoc) |
|---|---|---|
| AbstractSpectrDialogService | — | — |
| SpectrCellService | — | — |
| SpectrConfirmDialogService | root | — |
| SpectrCronService | — | — |
| SpectrCronUiDayState | — | — |
| SpectrCronUiHourState | — | — |
| SpectrCronUiMinuteState | — | — |
| SpectrCronUiMonthState | — | — |
| SpectrCronUiSecondState | — | — |
| SpectrCronUiYearState | — | — |
| SpectrDialogService | root | — |
| SpectrEventZoneService | — | — |
| SpectrFocusVisibleService | — | — |
| SpectrHintService | root | — |
| SpectrHoveredService | root | — |
| SpectrInputSelectOptionService | — | — |
| SpectrInputValidationTexts | — | — |
| SpectrInputZoneService | root | — |
| SpectrOverlayControl | — | — |
| SpectrOverlayService | root | — |
| SpectrOverscrollService | root | — |
| SpectrPageTabsService | — | — |
| SpectrResizeService | — | — |
| SpectrSidebarService | root | — |
| SpectrStickyRelativeService | — | — |
| SpectrTableRowService | — | — |
| SpectrTableService | — | — |
| SpectrTableSorterService | — | — |
| SpectrTableTreeService | — | — |
| SpectrTabsService | — | — |
| SpectrTdService | — | — |
| SpectrThGroupService | — | — |
| SpectrToastControl | root | — |
| SpectrToastService | root | — |
| SpectrTreeActiveNodeService | — | — |
| SpectrTreeConfigService | — | — |
| SpectrTreeService | — | — |
| SpectrZoneEventService | — | — |

## Модули

Всего: **43**.

| Модуль | Описание (JSDoc) |
|---|---|
| PolymorphModule | — |
| SpectrAccordionModule | — |
| SpectrBreadcrumbsModule | — |
| SpectrCalendarModule | — |
| SpectrChipsModule | — |
| SpectrConfirmPopupModule | — |
| SpectrCronInnerModule | — |
| SpectrCronModule | — |
| SpectrDataListModule | — |
| SpectrDropdownHostModule | — |
| SpectrExpandModule | — |
| SpectrGridModule | — |
| SpectrHeaderModule | — |
| SpectrInputCarouselModule | — |
| SpectrInputCommonModule | — |
| SpectrInputLayoutDateModule | — |
| SpectrInputLayoutDateRangeModule | — |
| SpectrInputLayoutDateRelativeModule | — |
| SpectrInputLayoutDateTimeModule | — |
| SpectrInputLayoutDateTimeRangeModule | — |
| SpectrInputLayoutMonthModule | — |
| SpectrInputLayoutMonthRangeModule | — |
| SpectrInputLayoutTimeModule | — |
| SpectrInputMultiSelectModule | — |
| SpectrInputNumberModule | — |
| SpectrInputPasswordModule | — |
| SpectrInputSelectModule | — |
| SpectrInputTextModule | — |
| SpectrInputZoneModule | — |
| SpectrMaskModule | — |
| SpectrNavigationModule | — |
| SpectrProgressModule | — |
| SpectrScrollbarModule | — |
| SpectrSliderModule | — |
| SpectrSplitterModule | — |
| SpectrStepperModule | — |
| SpectrStickyModule | — |
| SpectrTableModule | — |
| SpectrTabsModule | — |
| SpectrToastModule | — |
| SpectrTooltipModule | — |
| SpectrTreeModule | — |
| SpectrUiRootModule | — |

## DI-токены (InjectionToken)

Всего: **85**. Токены позволяют переопределять поведение компонентов (локализация, формат даты, поведение фокуса, анимации и т. д.).

| Токен | Назначение |
|---|---|
| AVATAR_GROUP_DATA_CONTEXT | avatar group data context |
| CALENDAR_RANGE_PART_TYPE | Calendar range part type |
| POLYMORPH_CONTEXT | Context from *polymorphOutlet |
| SPECTR_ACTIVE_ELEMENT | Active element on the document for ActiveZone |
| SPECTR_ANIMATION_OPTIONS | Options for SPECTR animations |
| SPECTR_AUTOFOCUS_HANDLER | Autofocusing handler |
| SPECTR_BADGE_OPTIONS | Default parameters for badge component |
| SPECTR_BUTTON_OPTIONS | Default parameters for button component |
| SPECTR_CALENDAR_DATA_STREAM | Stream that emits calendar data change |
| SPECTR_CALENDAR_MONTHS | [SPECTR_CALENDAR_MONTHS]: short calendar months i18n |
| SPECTR_COLUMN_SETTINGS | column settings texts |
| SPECTR_CONFIRM_POPUP_OPTIONS | Default parameters for tooltip directive |
| SPECTR_CRON | Localized for cron component |
| SPECTR_DATALIST_OPTIONS | Default parameters for datalist directive |
| SPECTR_DATE_CONVERTER | Token that specifies date conversion method |
| SPECTR_DATE_FORMAT | Active date format for Spectr UI |
| SPECTR_DATE_RANGE_VALUE_TRANSFORMER | Control value transformer for InputDateRange component |
| SPECTR_DATE_RIGHT_BUTTONS | Stream that emits right buttons |
| SPECTR_DATE_SEPARATOR | Date separator for Spectr UI components |
| SPECTR_DATE_TEXTS | date format i18n texts |
| SPECTR_DATE_TIME_RANGE_VALUE_TRANSFORMER | Control value transformer for InputDateTimeRange component |
| SPECTR_DATE_TIME_VALUE_TRANSFORMER | Control value transformer for InputDateTime component |
| SPECTR_DATE_VALUE_TRANSFORMER | Control value transformer of SpectrDay to custom value format for InputDate* components |
| SPECTR_DIALOGS_CLOSE | Default close event |
| SPECTR_DIALOG_CLOSE_STREAM | Dialogs closing stream |
| SPECTR_DROPDOWN_CONTROLLER | Controls configuration of hints |
| SPECTR_DROPDOWN_HOST_OPTIONS | Default parameters for dropdown host |
| SPECTR_ELEMENT_REF | ElementRef when you cannot use @Input for single time injection |
| SPECTR_EMPTY_LIST_TEXT | empty list i18n text |
| SPECTR_FILEUPLOAD_OPTIONS | Spectr file upload options |
| SPECTR_FILE_UPLOAD | Localized for file upload component |
| SPECTR_FIRST_DAY_OF_WEEK | The first day of the week index |
| SPECTR_FOCUSABLE_ITEM_ACCESSOR | A component that can be focused |
| SPECTR_HINT_CONTAINER_COMPONENT | SPECTR_HINT_CONTAINER_COMPONENT |
| SPECTR_HINT_GET_CONTEXT | SPECTR_HINT_GET_CONTEXT |
| SPECTR_HINT_ON_HOVER_ACTIVE | SPECTR_HINT_ON_HOVER_ACTIVE |
| SPECTR_HINT_OPTIONS | Default parameters for hint directive |
| SPECTR_INPUT_DATE_OPTIONS | [SPECTR_INPUT_DATE_OPTIONS]: Default parameters for date input component |
| SPECTR_INPUT_LAYOUT | input layout i18n base texts |
| SPECTR_INPUT_LAYOUT_DATE_RELATIVE | Localized for input layout date relative component |
| SPECTR_INPUT_LAYOUT_DATE_TIME | Localized for input layout date time component |
| SPECTR_INPUT_LAYOUT_DATE_TIME_RANGE | Localized for input layout date time range component |
| SPECTR_INPUT_TIME_OPTIONS | Default parameters for input time component |
| SPECTR_IS_IOS | iOS browser detection |
| SPECTR_IS_MOBILE | Mobile browser detection |
| SPECTR_MOBILE_CALENDAR | A component for mobile data picker |
| SPECTR_MONTHS | Localized months names |
| SPECTR_MONTH_FORMATTER | [SPECTR_MONTH_FORMATTER]: A function to get localized formatted month |
| SPECTR_MULTI_SELECT_OPTIONS | Default parameters for select |
| SPECTR_MUTATION_OBSERVER_OPTIONS | Default parameters for mutation observer directive |
| SPECTR_ORDERED_SHORT_WEEK_DAYS | Ordered calendars i18n texts |
| SPECTR_OTHER_DATE_TEXT | i18n |
| SPECTR_PAGINATOR | paginator texts |
| SPECTR_REMOVED_ELEMENT | Element currently being removed by AnimationEngine |
| SPECTR_SCROLL_REF | Scrollable container |
| SPECTR_SEARCH_TEXT | search i18n text |
| SPECTR_SELECT_OPTIONS | Default parameters for select |
| SPECTR_SHORT_WEEK_DAYS | calendars i18n texts |
| SPECTR_SPIN_TEXTS | spin i18n texts |
| SPECTR_TAKE_ONLY_TRUSTED_EVENTS | This token need for override behavior the |
| SPECTR_TEXTFIELD_HOST | [SPECTR_TEXTFIELD_HOST]: An interface to communicate with textfield based controls |
| SPECTR_TIME_FORMAT | Active time format for Spectr UI |
| SPECTR_TIME_TEXTS | time i18n texts |
| SPECTR_TIME_VALUE_TRANSFORMER | Control value transformer for InputTime component |
| SPECTR_TOAST_OPTIONS | Default parameters for toast component |
| SPECTR_TOGGLE_OPTIONS | Default parameters for toggle component |
| SPECTR_TOOLTIP_OPTIONS | Default parameters for tooltip directive |
| SPECTR_TREE_ACCESSOR | Controller for tracking value - SpectrTreeItemComponent pairs |
| SPECTR_TREE_CONTENT | Content for a tree item |
| SPECTR_TREE_CONTROLLER | Controller for expanding the tree |
| SPECTR_TREE_LEVEL | Nesting level of current TreeView node |
| SPECTR_TREE_LOADER | A service to load tree progressively |
| SPECTR_TREE_LOADING | A tree node placeholder for loading |
| SPECTR_TREE_NODE | A node of a tree view |
| SPECTR_TREE_SELECT_DROPDOWN_CONTROLLER | dropdown controller for tree select items |
| SPECTR_TREE_SELECT_ITEM | SPECTR_TREE_SELECT_ITEM |
| SPECTR_TREE_SELECT_ITEMS_VIEW_CONTAINER_REF | view container ref for tree select items |
| SPECTR_TREE_SELECT_ITEM_CHILDREN | SPECTR_TREE_SELECT_ITEM_CHILDREN |
| SPECTR_TREE_SELECT_ITEM_LEVEL | SPECTR_TREE_SELECT_ITEM_LEVEL |
| SPECTR_TREE_SELECT_ITEM_PARENTS | SPECTR_TREE_SELECT_ITEM_PARENTS |
| SPECTR_TREE_START | A tree node starting point |
| SPECTR_VALUE_ACCESSOR | Buffer token to pass NG_VALUE_ACCESSOR to a different Injector |
| SWITCHER_CONTAINER | element container for switcher |
| SWITCHER_VIEW_CONTAINER | view ref for switcher |
| SpectrOverlayContentToken | params for overlay |

## Константы

Всего: **163** (экспортируемые и документированные).

| Константа | Значение | Описание (JSDoc) |
|---|---|---|
| DATE_STREAM_FACTORY | (control, valueTransformer) => spectrReplayControlValueChangesFactory(control, valueTransf… | — |
| HINT_HOVERED_CLASS | '_hint_hovered' | — |
| INITIAL_SWITHCER_INDEX | 0 | — |
| RANGE_STREAM_FACTORY | (control, valueTransformer) => spectrReplayControlValueChangesFactory(control, valueTransf… | — |
| RANGE_TIME_STREAM_FACTORY | (control, valueTransformer) => spectrReplayControlValueChangesFactory(control, valueTransf… | — |
| SPECTR_ALWAYS_FALSE_HANDLER | () => false | — |
| SPECTR_ALWAYS_TRUE_HANDLER | () => true | — |
| SPECTR_ANIMATIONS_DURATION | spectrCreateTokenFromFactory('Duration of all animations in ms', () => (inject(SPECTR_REDU… | — |
| SPECTR_ASSETS_FOLDER | '/assets/spectr-ui/components' | — |
| SPECTR_ASSETS_FONT_FOLDER | '/assets/spectr-ui/fonts' | — |
| SPECTR_AUTOFOCUS_PROVIDERS | [     {         provide: SPECTR_AUTOFOCUS_HANDLER,         useFactory: spectrAutofocusHand… | — |
| SPECTR_BADGE_DEFAULT_OPTIONS | {     size: 's',     appearance: 'primary',     status: 'info', } | — |
| SPECTR_BUTTON_DEFAULT_OPTIONS | {     size: 'l',     appearance: 'primary',     appearanceType: 'fill',     hasIndicator: … | — |
| SPECTR_CHAR_BULLET | `\u2022` | — |
| SPECTR_CHAR_CURRENCY_SIGN | `\u00A4` | — |
| SPECTR_CHAR_ELLIPSIS | `\u2026` | — |
| SPECTR_CHAR_EM_DASH | `\u2014` | — |
| SPECTR_CHAR_EN_DASH | `\u2013` | — |
| SPECTR_CHAR_HYPHEN | `\u002D` | — |
| SPECTR_CHAR_LAQUO | `\u00AB` | — |
| SPECTR_CHAR_MINUS | `\u2212` | — |
| SPECTR_CHAR_NO_BREAK_SPACE | `\u00A0` | — |
| SPECTR_CHAR_PLUS | `\u002B` | — |
| SPECTR_CHAR_RAQUO | `\u00BB` | — |
| SPECTR_CHAR_ZERO_WIDTH_SPACE | `\u200B` | — |
| SPECTR_CONFIRM_POPUP_DEFAULT_OPTIONS | {     showDelay: 100,     size: 'm',     hideDelay: 100,     autoReposition: true,     mod… | — |
| SPECTR_COPY_TEXTS | spectrCreateTokenFromFactory('', spectrExtractI18n('copyTexts')) | — |
| SPECTR_CRON_UI_DAYS_OF_WEEK_CRON_KEYS | [     'SUN',     'MON',     'TUE',     'WED',     'THU',     'FRI',     'SAT', ] | — |
| SPECTR_CRON_UI_MONTH_CRON_KEYS | [     'JAN',     'FEB',     'MAR',     'APR',     'MAY',     'JUN',     'JUL',     'AUG', … | — |
| SPECTR_DATALIST_DEFAULT_OPTIONS | {     empty: '', } | — |
| SPECTR_DATE_FILLER_LENGTH | 10 | — |
| SPECTR_DATE_RANGE_FILLER_LENGTH | // TODO SPECTR_RANGE_SEPARATOR_CHAR instead of 3 2 * SPECTR_DATE_FILLER_LENGTH + 3 | — |
| SPECTR_DATE_TIME_SEPARATOR | ` ` | — |
| SPECTR_DATE_TIME_SEPARATOR_NGX | ` ` | — |
| SPECTR_DAYS_IN_LEAP_YEAR | 366 | — |
| SPECTR_DAYS_IN_NORMAL_YEAR | 365 | — |
| SPECTR_DAYS_IN_WEEK | 7 | — |
| SPECTR_DEFAULT_IDENTITY_MATCHER | (item1, item2) => item1 === item2 \|\| bothEmpty(item1, item2) | — |
| SPECTR_DEFAULT_MARKER_HANDLER | () => SPECTR_EMPTY_ARRAY | — |
| SPECTR_DEFAULT_MATCHER | (item, search, stringify = SPECTR_DEFAULT_STRINGIFY) => stringify(item).toLowerCase().incl… | — |
| SPECTR_DEFAULT_STRINGIFY | (item) => String(item) | — |
| SPECTR_DEFAULT_TREE_CONTROLLER | {     isExpanded: () => true,     toggle: SPECTR_EMPTY_FUNCTION, } | — |
| SPECTR_DIALOG_CLOSES_ON_BACK | spectrCreateToken('Is closing dialog on browser backward navigation enabled', of(false)) | — |
| SPECTR_DIALOG_DEFAULT_OPTIONS | {     size: 'm',     required: false,     closeable: true,     content: '',     footer: ''… | — |
| SPECTR_DIALOG_PROVIDERS | [     SpectrDestroyService,     {         provide: SPECTR_DIALOG_CLOSE_STREAM,         dep… | — |
| SPECTR_DIGIT_REGEXP | /\d/ | — |
| SPECTR_DROPDOWN_DEFAULT_MAX_HEIGHT | 400 | — |
| SPECTR_DROPDOWN_DEFAULT_MIN_HEIGHT | 80 | — |
| SPECTR_DROPDOWN_HOST_DEFAULT_OPTIONS | {     closeOnBackdrop: true,     width: null,     autoReposition: true,     placement: Spe… | — |
| SPECTR_EXPAND_LOADED | 'spectr-expand-loaded' | — |
| SPECTR_FIRST_DAY | new SpectrDay(SPECTR_MIN_YEAR, SPECTR_MIN_MONTH, SPECTR_MIN_DAY) | — |
| SPECTR_FIRST_DAY_WITH_TIME | new SpectrDateTime(SPECTR_FIRST_DAY, SPECTR_FIRST_TIME) | — |
| SPECTR_FIRST_TIME | new SpectrTime(0, 0, 0, 0) | — |
| SPECTR_FIXED_DROPDOWN_CONTROLLER_PROVIDER | [     {         provide: SPECTR_DROPDOWN_CONTROLLER,         deps: [[new Optional(), Spect… | — |
| SPECTR_HINT_DEFAULT_OPTIONS | {     showDelay: 500,     hideDelay: 200,     theme: null,     autoReposition: true,     /… | — |
| SPECTR_HOURS_IN_DAY | 24 | — |
| SPECTR_IDENTITY | identity | — |
| SPECTR_INPUT_DATE_DEFAULT_OPTIONS | {     icon: () => `calendar-blank`,     min: SPECTR_FIRST_DAY,     max: SPECTR_LAST_DAY,  … | — |
| SPECTR_INPUT_DATE_PROVIDERS | [     {         provide: SPECTR_CALENDAR_DATA_STREAM,         deps: [             [new Opt… | — |
| SPECTR_INPUT_DATE_RANGE_PROVIDERS | [     {         provide: SPECTR_CALENDAR_DATA_STREAM,         deps: [             [new Opt… | — |
| SPECTR_INPUT_DATE_TIME_PROVIDERS | [     SpectrDestroyService,     {         provide: SPECTR_CALENDAR_DATA_STREAM,         de… | — |
| SPECTR_INPUT_DATE_TIME_RANGE_PROVIDERS | [     {         provide: SPECTR_CALENDAR_DATA_STREAM,         deps: [             [new Opt… | — |
| SPECTR_INPUT_TIME_DEFAULT_OPTIONS | {     mode: `HH:MM`,     maxValues: SPECTR_MAX_TIME_VALUES,     itemSize: `m`, } | — |
| SPECTR_IS_ANDROID | spectrCreateTokenFromFactory('Mobile browser that is not iOS', () => inject(SPECTR_IS_MOBI… | — |
| SPECTR_LAST_DAY | new SpectrDay(SPECTR_MAX_YEAR, SPECTR_MAX_MONTH, 31) | — |
| SPECTR_LAST_DAY_WITH_TIME | new SpectrDateTime(SPECTR_LAST_DAY, SPECTR_LAST_TIME) | — |
| SPECTR_LAST_PUNCTUATION_MARK_REGEXP | /[.,\\/#!$%\\^&\\* | — |
| SPECTR_LAST_TIME | new SpectrTime(23, 59, 0, 0) | — |
| SPECTR_LATIN_AND_NUMBERS_REGEXP | /[A-z\|0-9]/ | — |
| SPECTR_LATIN_REGEXP | /[A-z]/ | — |
| SPECTR_LEADING_ZEROES_REGEXP | /^0+/ | — |
| SPECTR_LEFT_ALIGNED_DROPDOWN_CONTROLLER_PROVIDER | [     {         provide: SPECTR_DROPDOWN_CONTROLLER,         deps: [[new Optional(), Spect… | — |
| SPECTR_LOCAL_DATE_PROVIDER | {     provide: SPECTR_DATE_CONVERTER,     useValue: 'Local', } | — |
| SPECTR_MASK_SYMBOLS_REGEXP | /[ \-_()]/g | — |
| SPECTR_MAX_MONTH | 11 | — |
| SPECTR_MAX_TIME_VALUES | {     HH: 23,     MM: 59,     SS: 59,     MS: 999, } | — |
| SPECTR_MAX_YEAR | 9999 | — |
| SPECTR_MILLISECONDS_IN_DAY | SPECTR_MILLISECONDS_IN_HOUR * SPECTR_HOURS_IN_DAY | — |
| SPECTR_MILLISECONDS_IN_HOUR | SPECTR_MILLISECONDS_IN_MINUTE * SPECTR_MINUTES_IN_HOUR | — |
| SPECTR_MILLISECONDS_IN_MINUTE | SPECTR_MILLISECONDS_IN_SECOND * SPECTR_SECONDS_IN_MINUTE | — |
| SPECTR_MILLISECONDS_IN_SECOND | 1000 | — |
| SPECTR_MINUTES_IN_HOUR | 60 | — |
| SPECTR_MIN_DAY | 1 | — |
| SPECTR_MIN_MONTH | 0 | — |
| SPECTR_MIN_YEAR | 0 | — |
| SPECTR_MONTHS_IN_YEAR | 12 | — |
| SPECTR_MULTI_SELECT_DEFAULT_OPTIONS | {     items: [],     chooseAllItem: null,     icon: null,     searchable: false,     autoR… | — |
| SPECTR_MUTATION_OBSERVER_DEFAULT_OPTIONS | {     config: {         childList: true,         attributes: true,         subtree: true, … | — |
| SPECTR_NON_DIGITS_REGEXP | /\D+/g | — |
| SPECTR_NON_DIGIT_REGEXP | /\D/ | — |
| SPECTR_OVERLAY_BACKDROP_NO_POINTERS | 'no-pointers' | — |
| SPECTR_POLLING_TIME | 1000 / 15 | — |
| SPECTR_RANGE_SEPARATOR_CHAR | ` - ` | — |
| SPECTR_REDUCED_MOTION | spectrCreateTokenFromFactory('', () => inject(DOCUMENT).defaultView?.matchMedia?.('(prefer… | — |
| SPECTR_SCROLLABLE | 'spectr-scrollable' | — |
| SPECTR_SCROLL_INTO_VIEW | 'spectr-scroll-into-view' | — |
| SPECTR_SECONDS_IN_MINUTE | 60 | — |
| SPECTR_SELECT_DEFAULT_OPTIONS | {     items: [],     searchable: false,     autoReposition: false,     search: null,     i… | — |
| SPECTR_STRICT_MATCHER | (item, search, stringify = SPECTR_DEFAULT_STRINGIFY) => stringify(item).toLowerCase() === … | — |
| SPECTR_TABLE_PROVIDER | [     SpectrDestroyService,     SpectrTableSortPipe,     {         provide: SpectrTableDir… | — |
| SPECTR_TABLE_PROVIDERS | [     {         provide: INTERSECTION_ROOT_MARGIN,         useValue: `10000px 10000px 1000… | — |
| SPECTR_TOAST_DEFAULT_OPTIONS | {     position: SpectrToastPosition.TOP_RIGHT,     timer: 5000,     title: '',     appeara… | — |
| SPECTR_TOGGLE_DEFAULT_OPTIONS | {     icons: {         toggleOff: '',         toggleOn: '',     },     singleColor: false,… | — |
| SPECTR_TOOLTIP_DEFAULT_OPTIONS | {     showDelay: 100,     hideDelay: 100,     theme: null,     autoReposition: true,     m… | — |
| SPECTR_TREE_ITEM_CONTENT | new PolymorphComponent(SpectrTreeItemContentComponent) | — |
| SPECTR_TREE_ITEM_PROVIDERS | [     {         provide: SPECTR_TREE_LEVEL,         deps: [[new SkipSelf(), SPECTR_TREE_LE… | — |
| SPECTR_TREE_OPTIONS | {} | — |
| SPECTR_UTC_DATE_PROVIDER | {     provide: SPECTR_DATE_CONVERTER,     useValue: 'UTC', } | — |
| SPECTR_VALUE_ACCESSOR_PROVIDER | {     provide: SPECTR_VALUE_ACCESSOR,     deps: [[new Optional(), new Self(), NG_VALUE_ACC… | — |
| SWITCHER_DEFAULT_ITEMS_TRACK_BY | (idx, item) => {     return !!item | — |
| SpectrCronDefaultObjectValue | {     second: '0',     minute: '0',     hour: '*',     month: '*',     dayOfMonth: '*',   … | — |
| SpectrDataListOptionsProvider | (options) => ({     provide: SPECTR_DATALIST_OPTIONS,     useValue: { ...SPECTR_DATALIST_D… | — |
| SpectrOverlayBasePlacement | {     ...spectrOverlayBaseType, } | — |
| SpectrOverlayInsidePlacement | {     ...spectrOverlayYSide,     ...spectrOverlayInnerSide, } | — |
| SpectrOverlayOutsidePlacement | {     ...spectrOverlayYSide,     ...spectrOverlayLeftSide, } | — |
| TIME_STREAM_FACTORY | (control, valueTransformer) => spectrReplayControlValueChangesFactory(control, valueTransf… | — |
| getShortWeekDays | (days) => {     const firstDayOfWeekIndex = inject(SPECTR_FIRST_DAY_OF_WEEK) | — |
| handleTimeLimit | (date, time, limitDate, limitTime, isMin = true) => {     if (!limitTime \|\| !limitDate \|\| … | — |
| isPolymorphComponent | (content) => {     return content instanceof PolymorphComponent | — |
| isPolymorphDirective | (content) => {     return content instanceof PolymorphTemplate | — |
| isPolymorphPrimitive | (content) => {     if (isPolymorphTemplate(content))         return false | — |
| isPolymorphTemplate | (content) => {     if (isPolymorphDirective(content)) {         return true | — |
| spectrBadgeOptionsProvider | (options) => ({     provide: SPECTR_BADGE_OPTIONS,     useValue: { ...SPECTR_BADGE_DEFAULT… | — |
| spectrButtonOptionsProvider | (options) => ({     provide: SPECTR_BUTTON_OPTIONS,     useValue: { ...SPECTR_BUTTON_DEFAU… | — |
| spectrChangeDateSeparator | (dateString, newDateSeparator) => dateString.replace(/[^0-9A-Za-zА-Яа-я]/gi, newDateSepara… | — |
| spectrConfirmPopupOptionsProvider | (options) => ({     provide: SPECTR_CONFIRM_POPUP_OPTIONS,     useValue: { ...SPECTR_CONFI… | — |
| spectrConvertToSundayFirstWeekFormat | (weekDaysNames) => {     const sundayIndex = weekDaysNames.length - 1 | — |
| spectrCronHRToString | SpectrCronHRExpressionDescriptor.toString | — |
| spectrDefaultCarouselControlsState | {     leftCtrlDisabled: true,     stepleftCtrlDisabled: true,     stepRightCtrlDisabled: t… | — |
| spectrDropdownAnimation | trigger('spectrDropdownAnimation', [     transition(`* => ${"fadeInTop" /* SpectrDropdownA… | — |
| spectrDropdownHostOptionsProvider | (options) => ({     provide: SPECTR_DROPDOWN_HOST_OPTIONS,     useValue: { ...SPECTR_DROPD… | — |
| spectrFadeIn | trigger('spectrFadeIn', [     transition(':enter', [style({ opacity: 0 }), animate(TRANSIT… | — |
| spectrFadeInBottom | trigger('spectrFadeInBottom', [     transition(':enter', [         style({ transform: 'tra… | — |
| spectrFadeInList | trigger('spectrFadeInList', [     transition('* => *', [         query(':enter', [style({ … | — |
| spectrFadeInTop | trigger('spectrFadeInTop', [     transition(':enter', [         style({ transform: 'transl… | — |
| spectrFileUploadDefaultOptions | {     showRetryButtons: true, } | — |
| spectrHeightCollapse | trigger('spectrHeightCollapse', [     transition(':enter', [style({ height: 0 }), animate(… | — |
| spectrHeightCollapseList | trigger('spectrHeightCollapseList', [     transition('* => *', [         query(':enter', [… | — |
| spectrHintOptionsProvider | (options) => ({     provide: SPECTR_HINT_OPTIONS,     useValue: { ...SPECTR_HINT_DEFAULT_O… | — |
| spectrInputCarouselDefaultControlsState | spectrDefaultCarouselControlsState | — |
| spectrInputDateOptionsProvider | (options) => ({     provide: SPECTR_INPUT_DATE_OPTIONS,     useValue: { ...SPECTR_INPUT_DA… | — |
| spectrInputTimeOptionsProvider | (options) => ({     provide: SPECTR_INPUT_TIME_OPTIONS,     useValue: { ...SPECTR_INPUT_TI… | — |
| spectrIsDateMode | (dateMode) => [`DMY`, `YMD`, `MDY`].includes(dateMode) | — |
| spectrMultiSelectOptionsProvider | (options) => ({     provide: SPECTR_MULTI_SELECT_OPTIONS,     useValue: { ...SPECTR_MULTI_… | — |
| spectrMutationObserverOptionsProvider | (options) => ({     provide: SPECTR_MUTATION_OBSERVER_OPTIONS,     useValue: { ...SPECTR_M… | — |
| spectrScaleIn | trigger('spectrScaleIn', [     transition(':enter', [style({ transform: 'scale(0)' }), ani… | — |
| spectrScaleInList | trigger('spectrScaleInList', [     transition('* => *', [         query(':enter', [       … | — |
| spectrSelectOptionsProvider | (options) => ({     provide: SPECTR_SELECT_OPTIONS,     useValue: { ...SPECTR_SELECT_DEFAU… | — |
| spectrSlideIn | trigger('spectrSlideIn', [     transition(`* => left`, [style({ transform: 'translateX(-10… | — |
| spectrSlideInBottom | trigger('spectrSlideInBottom', [     transition(':enter', [style({ transform: 'translateY(… | — |
| spectrSlideInBottomList | trigger('spectrSlideInBottomList', [     transition('* => *', [         query(':enter', [ … | — |
| spectrSlideInLeft | trigger('spectrSlideInLeft', [     transition(':enter', [style({ transform: 'translateX(-1… | — |
| spectrSlideInLeftList | trigger('spectrSlideInLeftList', [     transition('* => *', [         query(':enter', [   … | — |
| spectrSlideInRight | trigger('spectrSlideInRight', [     transition(':enter', [style({ transform: 'translateX(1… | — |
| spectrSlideInRightList | trigger('spectrSlideInRightList', [     transition('* => *', [         query(':enter', [  … | — |
| spectrSlideInTop | trigger('spectrSlideInTop', [     transition(':enter', [         style({ transform: 'trans… | — |
| spectrSlideInTopList | trigger('spectrSlideInTopList', [     transition('* => *', [         query(':enter', [    … | — |
| spectrSvgNodeFilter | ((node) => 'ownerSVGElement' in node ? NodeFilter.FILTER_REJECT : NodeFilter.FILTER_ACCEPT… | — |
| spectrToastOptionsProvider | (options) => ({     provide: SPECTR_TOAST_OPTIONS,     useValue: { ...SPECTR_TOAST_DEFAULT… | — |
| spectrToggleOptionsProvider | (options) => ({     provide: SPECTR_TOGGLE_OPTIONS,     useValue: { ...SPECTR_TOGGLE_DEFAU… | — |
| spectrTooltipOptionsProvider | (options) => ({     provide: SPECTR_TOOLTIP_OPTIONS,     useValue: { ...SPECTR_TOOLTIP_DEF… | — |
| spectrWidthCollapse | trigger('spectrWidthCollapse', [     transition(':enter', [style({ width: 0 }), animate(TR… | — |
| spectrWidthCollapseList | trigger('spectrWidthCollapseList', [     transition('* => *', [         query(':enter', [s… | — |

## Утилитные функции

Всего: **79** (все экспортируются).

| Функция | Описание (JSDoc) |
|---|---|
| canShowCronListItem | — |
| getArrWithStringNumbers | — |
| getArrWithWeekNumber | — |
| getCarousel | — |
| getCarouselWeek | — |
| getDefaultRelativeDateMenuItems | — |
| getProviderSpectrDateLeftButtons | — |
| getSpectrLabelPosition | — |
| scrollRefFactory | — |
| spectrAsDataList | — |
| spectrAsFocusableItemAccessor | — |
| spectrAsTextfieldHost | — |
| spectrAutofocusHandlerFactory | — |
| spectrBlurNativeFocused | — |
| spectrCanScroll | — |
| spectrCeil | — |
| spectrClamp | — |
| spectrContainsOrAfter | — |
| spectrConvertDayToType | — |
| spectrCreateDateNgxMask | — |
| spectrCreateDateTimeNgxMask | — |
| spectrCreateDateTimeRangeMask | — |
| spectrCreateTimeNgxMask | — |
| spectrCronConvertToObject | — |
| spectrDialogCloseStreamFactory | — |
| spectrFixedDropdownControllerFactory | — |
| spectrFloor | — |
| spectrFocusVisibleObservable | — |
| spectrGetActualTarget | — |
| spectrGetElementOffset | — |
| spectrGetInputDateTimeNativeTransformer | — |
| spectrGetNativeFocused | — |
| spectrGetOriginalArrayFromQueryList | — |
| spectrGetScrollParent | — |
| spectrGetShadow | — |
| spectrHexToRgb | — |
| spectrInRange | — |
| spectrIsAlive | — |
| spectrIsApple | — |
| spectrIsCurrentTarget | — |
| spectrIsEdge | — |
| spectrIsEdgeOlderThan | — |
| spectrIsFirefox | — |
| spectrIsIE | — |
| spectrIsIos | — |
| spectrIsNativeFocused | — |
| spectrIsNativeFocusedIn | — |
| spectrIsNativeKeyboardFocusable | — |
| spectrIsNativeMouseFocusable | — |
| spectrIsNumber | — |
| spectrIsPresent | — |
| spectrIsSafari | — |
| spectrIsString | — |
| spectrIsTextOverflow | — |
| spectrLeftAlignedDropdownControllerFactory | — |
| spectrMouseDragFinishFrom | — |
| spectrNormalizeToIntNumber | — |
| spectrNullableSame | — |
| spectrPressedObservable | — |
| spectrPreventDefault | — |
| spectrQuantize | — |
| spectrQueryListChanges | — |
| spectrReplayControlValueChangesFactory | — |
| spectrReplayedValueChangesFrom | — |
| spectrRgbToHex | — |
| spectrRound | — |
| spectrSetNativeFocused | — |
| spectrSizeBigger | — |
| spectrStopPropagation | — |
| spectrSum | — |
| spectrTableDefaultColumnSort | — |
| spectrTimeLimitWithinRange | — |
| spectrToInt | — |
| spectrToPx | — |
| spectrToRadians | — |
| spectrZoneFree | — |
| spectrZoneFull | — |
| spectrZoneOptimized | — |
| treeLevelFactory | — |

## Сводка

| Тип | Количество |
|---|---|
| Компоненты | 127 |
| Директивы | 119 |
| Пайпы | 16 |
| Сервисы | 38 |
| Модули | 43 |
| DI-токены | 85 |
| Константы | 163 |
| Функции | 79 |
