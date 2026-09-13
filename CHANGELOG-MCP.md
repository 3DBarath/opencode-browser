# V0.0.6

### Initial Release
  - Stealth & anti-fingerprinting: stealth_enable, stealth_disable, stealth_status (webdriver, canvas, webgl, audio, fonts, codecs, permissions spoofing)
  - Proxy management: set_proxy, clear_proxy, get_proxy, set_webrtc_policy, get_webrtc_policy
  - Dialog & form automation: handle_dialog, fill_form, check, uncheck, wait_for_text
  - Assertion tools: verify_element_visible, verify_text_visible, verify_value, generate_locator
  - Lighthouse & performance: lighthouse_audit (heuristic), performance_insight (Core Web Vitals)
  - Screencast: screencast_start, screencast_stop
  - Device emulation: resize_page, emulate (unified viewport, UA, locale, timezone, colorScheme)
  - Advanced mouse: mouse_move, mouse_down, mouse_up, mouse_wheel, click_at
  - Heap analysis: heap_summary, heap_query_objects
  - Storage completeness: cookie_clear, localstorage_list, localstorage_delete, sessionstorage_set/get/delete/clear
  - Network tools: route_list, unroute, network_state_set, get_network_request
  - IndexedDB: indexeddb_list, indexeddb_clear
  - Extension management: list_extensions, enable_extension, disable_extension, reload_extension, trigger_extension_action
  - PWA & WebMCP: pwa_check, list_webmcp_tools, execute_webmcp_tool
  - Bugfixes: single global debugger event listener (fixes memory leak), screenshot/PDF return proper image/resource types
