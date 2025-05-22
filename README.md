# inventory
gantt
    dateFormat  YYYY-MM-DD
    axisFormat  %Y-%m
    %% Set the current date to highlight where we are on the timeline



    title Device Support & License Timelines

    section Cisco Switch (12345CI)
    Hardware Support        :active, cs_hw_support, 2025-02-15, 2026-02-14
    End-of-Life             :milestone, after cs_hw_support, 2030-01-01

    section Juniper Firewall (12345J123)
    Hardware Support        :active, jf_hw_support, 2024-12-08, 2025-12-08
    FW-ADV-1Y License       :active, jf_lic_fw, 2025-02-14, 2026-02-13
    End-of-Life             :milestone, after jf_lic_fw, 2029-05-01

    section Cisco 9001 Router (343434R343)
    Hardware Support        :active, cr_hw_support, 2025-01-10, 2026-01-09
    RTR-ADV-1Y License      :active, cr_lic_rtr, 2025-02-20, 2026-02-19
    End-of-Life             :milestone, after cr_lic_rtr, 2030-01-01
