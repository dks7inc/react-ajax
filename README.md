# react-ajax

_fetchComments() {
    $.ajax({
      method: 'GET',
      url: 'comments.json',
      success: (comments) => this.setState({comments})
    });
  }
