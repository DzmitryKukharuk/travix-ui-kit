Basic Sliding Panel:

    <div>
      <button
        onClick={() => setState({ isSlidingPanelOpen: !state.isSlidingPanelOpen })}
      >Open panel</button>
      <SlidingPanel
        active={state.isSlidingPanelOpen}
        onClose={() => setState({ isSlidingPanelOpen: false })}
        title="Panel Title"
      >
        This is an example<br/>
        Of how simple it is to use<br/>
        Our sliding panel.<br/><br/>
        <button data-rel="close">Close</button>
      </SlidingPanel>
    </div>
